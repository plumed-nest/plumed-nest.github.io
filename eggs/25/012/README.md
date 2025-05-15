**Project ID:** [plumID:25.012]({{ '/' | absolute_url }}eggs/25/012/)  
**Name:**  A Machine Learning-Driven, Probability-Based Approach to Enzyme Catalysis  
**Archive:** [ https://github.com/sudipdas789/Committor_Amylase/raw/main/Committor_Amylase_PLUMED_NEST.zip](https://github.com/sudipdas789/Committor_Amylase/raw/main/Committor_Amylase_PLUMED_NEST.zip)  
**Category:**  bio  
**Keywords:**  enzyme catalysis, transition state, structure-activity relationship, free energy surface, reaction mechanism, water, alpha-amylase, sugar, QM/MM MD, OPES, committor function, machine learning  
**PLUMED version:**  2.9  
**Contributor:**  Sudip Das  
**Submitted on:** 15 May 2025  
**Publication:** [S. Das, U. Raucci, E. Trizio, P. Kang, R. Neves, M. Ramos, M. Parrinello, A Machine Learning-Driven, Probability-Based Approach to Enzyme Catalysis (2025)](http://dx.doi.org/10.26434/chemrxiv-2025-dqb0g)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [OPES_Enhanced_Sampling_with_Committor/plumed.dat](./data/OPES_Enhanced_Sampling_with_Committor/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/OPES_Enhanced_Sampling_with_Committor/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/OPES_Enhanced_Sampling_with_Committor/plumed.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [..._with_Committor/plumed_distances_49descriptors.dat](./data/OPES_Enhanced_Sampling_with_Committor/plumed_distances_49descriptors.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/OPES_Enhanced_Sampling_with_Committor/plumed_distances_49descriptors.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/OPES_Enhanced_Sampling_with_Committor/plumed_distances_49descriptors.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [..._with_Committor/plumed_positions_49descriptors.dat](./data/OPES_Enhanced_Sampling_with_Committor/plumed_positions_49descriptors.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/OPES_Enhanced_Sampling_with_Committor/plumed_positions_49descriptors.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/OPES_Enhanced_Sampling_with_Committor/plumed_positions_49descriptors.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
  
**Last tested:**  15 May 2025, 08:11:14
  
**Project description and instructions**  
This egg contains the input files for replicating committor training and enhanced sampling OPES simulations with a smoother version of the committor as a CV for calculating FES, reaction mechanisms and TS ensembles for alpha-amylase enzyme catalyzing a sugar substrate. The CV was trained with Pytorch version 1.8 and the simulations were run with GROMACS 2021.5, CP2K 9.1, and PLUMED 2.9. 

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=FLUSH,POSITION,COMBINE,CUSTOM,ENERGY,PRINT,CELL,MATHEVAL,OPES_METAD,INCLUDE,BIASVALUE,TORSION,UNITS,DISTANCE,LOAD,COORDINATION" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 15 May 2025: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:25.012" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:25.012](https://www.plumed-nest.org/eggs/25/012/badge.svg)](https://www.plumed-nest.org/eggs/25/012/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/25/012/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/25/012/badge.svg" alt="plumID:25.012"&gt;&lt;/a&gt;</pre>
  </div>
</div>
