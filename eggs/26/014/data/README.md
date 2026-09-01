# PLUMED-NEST submission: GPR15L–polySia dissociation free energy (DFE) metadynamics

System: GPR15L (protein) bound to α2,8-polysialic acid chains of degree of
polymerization DP5, DP10 and DP20, in aqueous solution (amber99sb-ildn +
GLYCAM06h, TIP3P, NaCl), GROMACS 2022.3 + PLUMED 2.8.3.

CV: distance between the center of mass of the protein (atoms 1-256) and the
center of mass of the polySia chain (DP5: atoms 938-1120, DP10: 938-1292,
DP20: see plumed.dat), restricted by an UPPER_WALLS at 7.3 nm
(KAPPA=10000 kJ/mol/nm^2).

Well-tempered-free metadynamics on the COM distance:
SIGMA=0.005 nm, HEIGHT=0.4184 kJ/mol, PACE=45 steps (dt=2 fs),
bias factor removed (standard metadynamics), Gaussian deposition in HILLS,
COLVAR printed every 500 steps.

Ensemble: 13 (DP5) / 15 (DP10) / 22 (DP20) replicas × 10 ns each, started from
the same bound conformation with different velocity seeds (BASE_SEED=2007,
seeds assigned per replica in run.sh). The dissociation free energy (DFE)
profiles were obtained by reweighting/analysis of these ensembles (see
analysis/receptor_and_complexes_analysis.ipynb in the parent repository).

Each DP directory contains everything needed to rerun:

- plumed.dat        PLUMED input (identical except gB atom range per chain length)
- complex.pdb       bound GPR15L–polySia starting structure
- topol.top, top/   GROMACS topology (amber99sb-ildn + GLYCAM06h via top/*.itp)
- index.ndx         GROMACS index file
- mdp/              GROMACS run parameters: ions, emin, nvt, nvt_seeded (with
                    GEN_SEED placeholder), npt, md (equilibration), md_short
                    (10 ns production with PLUMED)
- run.sh            self-contained workflow: writes plumed.dat, extracts the
                    bound conformation, and loops the replicas
                    (nvt_seeded -> npt -> md_short -plumed ../plumed.dat);
                    SBATCH header and binary paths are those of the NTNU
                    triumvirate cluster and serve as documentation — adjust
                    $gmx / $plumed / PLUMED_KERNEL for your installation
- continue.sh       continuation script

To reproduce:

    cd DP5   # or DP10, DP20
    ./run.sh

GROMACS 2022.3 patched with PLUMED 2.8.3 was used for the published results.
