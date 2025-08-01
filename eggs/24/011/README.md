**Project ID:** [plumID:24.011]({{ '/' | absolute_url }}eggs/24/011/)  
**Name:**  Computing the Committor with the Committor, an Anatomy of the Transition State Ensemble  
**Archive:** [ https://github.com/alphatestK/Committor/raw/main/plumed_nest.zip](https://github.com/alphatestK/Committor/raw/main/plumed_nest.zip)  
**Category:**  methods  
**Keywords:**  committor, machine learning  
**PLUMED version:**  2.9  
**Contributor:**  Peilin Kang  
**Submitted on:** 22 Apr 2024  
**Publication:** [P. Kang, E. Trizio, M. Parrinello, Computing the committor with the committor to study the transition state ensemble. Nature Computational Science. 4, 451–460 (2024)](http://dx.doi.org/10.1038/s43588-024-00645-0)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [ala2/data/template/plumed.dat](./data/ala2/data/template/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/ala2/data/template/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/ala2/data/template/plumed.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [chignolin/data/template/plumed_biased.dat](./data/chignolin/data/template/plumed_biased.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/chignolin/data/template/plumed_biased.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/chignolin/data/template/plumed_biased.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [chignolin/data/template/plumed_unbiased.dat](./data/chignolin/data/template/plumed_unbiased.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/chignolin/data/template/plumed_unbiased.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/chignolin/data/template/plumed_unbiased.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [dasa/data/template/plumed.dat](./data/dasa/data/template/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/dasa/data/template/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/dasa/data/template/plumed.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [dasa/data/template/plumed_distances.dat](./data/dasa/data/template/plumed_distances.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/dasa/data/template/plumed_distances.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/dasa/data/template/plumed_distances.dat.plumed_master.stderr) |  
| [dasa/data/template/plumed_positions.dat](./data/dasa/data/template/plumed_positions.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/dasa/data/template/plumed_positions.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/dasa/data/template/plumed_positions.dat.plumed_master.stderr) |  
| [mueller/iter1/plumed.dat](./data/mueller/iter1/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/mueller/iter1/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/mueller/iter1/plumed.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
  
**Last tested:**  25 Jul 2025, 11:35:07
  
**Project description and instructions**  
The Müller-Brown potential’s simulations have been performed using the MD engine in the ves_md_linearexpansion module of PLUMED. The vacuum alanine dipeptide simulations have been carried out using the GROMACS v2021.5 MD engine and the Amber99-SB force field. The DASA reaction simulations have been carried out using the CP2K-8.1 software package at PM6 semi-empirical level. For the study of folding and unfolding of chignolin in explicit solvent, we performed our simulations using GROMACS v2021.5 the CHARMM22∗ force field and TIP3P water force field. 

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=POSITION,UPPER_WALLS,BIASVALUE,CUSTOM,ENDPLUMED,MOLINFO,UNITS,LOWER_WALLS,LOAD,DISTANCE,RMSD,TORSION,CELL,INCLUDE,PRINT,GROUP,ENERGY,MATHEVAL,COORDINATION,WHOLEMOLECULES" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 22 Apr 2024: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:24.011" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:24.011](https://www.plumed-nest.org/eggs/24/011/badge.svg)](https://www.plumed-nest.org/eggs/24/011/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/24/011/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/24/011/badge.svg" alt="plumID:24.011"&gt;&lt;/a&gt;</pre>
  </div>
</div>
