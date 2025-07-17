````markdown
# Imidazole Diffusion in SALEM-2 MOF

This repository contains data, analysis tools, templates, and figures from our study of imidazole diffusion through 4MR and 6MR windows in SALEM-2 MOF using OPES-enhanced machine learning potentials (DeePMD).

![Graphical abstract](TOC.png)

## Repository Structure

### `data/`
Contains processed datasets, production-grade DeePMD models, and results of molecular dynamics simulations (OPES enhanced sampling).

### `figures/`
Publication-ready figures used in the paper.

### `notebooks/`
Jupyter notebooks for data analysis, visualization, and post-processing of simulation results.

### `templates/`
Input file templates and configuration files for LAMMPS MD + PLUMED-OPES simulations. Also includes training scripts for DeePMD models.

## Citation

If you use any data, code, or resources from this repository, please cite our work as follows:

```bibtex
@article{Ethirajan2025OPES,
  year     = {2025},
  title    = {{OPES}-Enhanced Machine Learning Potentials Capture Node-Assisted Diffusion and Ring-Opening in {SALEM}-2},
  author   = {Ethirajan, Sudheesh Kumar and Kulkarni, Ambarish R},
  doi      = {10.26434/chemrxiv-2025-mg7qj},
  abstract = {Machine learning potentials ({MLPs}) can help bridge the length- and time-scale gaps required to study functional nanoporous materials at ab initio accuracy. {MLPs} are usually trained using quantum chemical data obtained from traditional molecular dynamics ({MD}) simulations. These {MD} simulations predominantly sample near-equilibrium configurations on the potential energy surface. This often limits the {MLPs} ability to accurately describe less favorable, high-energy configurations. We address this challenge by introducing an active learning framework based on the On-the-fly-Probability-Enhanced-Sampling ({OPES}) method. Using imidazole diffusion in the {SALEM}-2 metal-organic framework ({MOF}) as an example, our approach employs a time-dependent {OPES} bias with expanded temperature- and distance-based collective variables. This allows extended {MD} simulations of linker molecule diffusion over 5 ns with ab initio accuracy. Interestingly, our simulations reveal a novel ring-opening phenomenon during imidazole diffusion across the four-membered window. This process, which is not captured by classical potentials, suggests the advantage of using {OPES}-based training curricula to study diffusion in {MOFs}.}
}
```

## Contact

For questions regarding the data or methodology, please contact the corresponding authors or open an issue in this repository and tag @skethirajan.
````
