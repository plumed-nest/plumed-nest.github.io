**Project ID:** [plumID:20.014]({{ '/' | absolute_url }}eggs/20/014/)  
**Name:**  amyloid beta small molecule interaction  
**Archive:** [ https://github.com/vendruscolo-lab/amyloid-beta_small_mol/raw/master/Metadynamic_metainference/PLUMED_input_files.zip](https://github.com/vendruscolo-lab/amyloid-beta_small_mol/raw/master/Metadynamic_metainference/PLUMED_input_files.zip)  
**Category:**  bio  
**Keywords:**  intrinsically disordered proteins, disordered proteins, IDPs, fuzzy binding, small molecule, drugs, entropy, binding, Alzheimer's disease, amyloid beta  
**PLUMED version:**  2.6.0  
**Contributor:**  Gabriella Heller  
**Submitted on:** 08 May 2020  
**Last revised:** 06 Nov 2020  
**Publication:** [G. T. Heller, F. A. Aprile, T. C. T. Michaels, R. Limbocker, M. Perni, F. S. Ruggeri, B. Mannini, T. Löhr, M. Bonomi, C. Camilloni, A. De Simone, I. C. Felli, R. Pierattelli, T. P. J. Knowles, C. M. Dobson, M. Vendruscolo, Small-molecule sequestration of amyloid-β as a drug discovery strategy for Alzheimer’s disease. Science Advances. 6 (2020)](http://dx.doi.org/10.1126/sciadv.abb5924)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [PLUMED_input_files/AB42_alone/plumed/plumed.dat](./data/PLUMED_input_files/AB42_alone/plumed/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/PLUMED_input_files/AB42_alone/plumed/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/PLUMED_input_files/AB42_alone/plumed/plumed.dat.plumed_master.stderr) |  
| [...ED_input_files/AB42_and_10074_G5/plumed/plumed.dat](./data/PLUMED_input_files/AB42_and_10074_G5/plumed/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/PLUMED_input_files/AB42_and_10074_G5/plumed/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/PLUMED_input_files/AB42_and_10074_G5/plumed/plumed.dat.plumed_master.stderr) |  
  
**Last tested:**  04 Sep 2025, 08:32:16
  
**Project description and instructions**  
This study uses metadynamic metainference simulations restrained with NMR chemical shift data to determine the bound and unbound ensembles of a disordered peptide (amyloid beta) in the presence and absence of a small, drug-like molecule. We used PLUMED version 2.6.0 and GROMACS 2018.3.

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=ENDPLUMED,GROUP,ANTIBETARMSD,DIHCOR,COORDINATION,CS2BACKBONE,INCLUDE,PBMETAD,ALPHARMSD,COMBINE,TORSION,PRINT,STATS,WHOLEMOLECULES,MOLINFO,ENSEMBLE,PARABETARMSD,METAINFERENCE,FLUSH,GYRATION" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 08 May 2020: original submission  
**[v2]** 06 Nov 2020: updated doi  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:20.014" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:20.014](https://www.plumed-nest.org/eggs/20/014/badge.svg)](https://www.plumed-nest.org/eggs/20/014/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/20/014/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/20/014/badge.svg" alt="plumID:20.014"&gt;&lt;/a&gt;</pre>
  </div>
</div>
