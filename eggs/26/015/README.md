**Project ID:** [plumID:26.015]({{ '/' | absolute_url }}eggs/26/015/)  
**Name:**  Ensemble Dynamics  
**Archive:** [ https://github.com/Flofega/EnsembleDynamicsPaper/raw/main/plumednest.zip](https://github.com/Flofega/EnsembleDynamicsPaper/raw/main/plumednest.zip)  
**Category:**  methods  
**Keywords:**  State Exploration, Protein Folding, Drug Binding, Phase Transition  
**PLUMED version:**  2.10  
**Contributor:**  Florian M. Dietrich  
**Submitted on:** 26 Oct 2026  
**Publication:** [F. M. Dietrich, M. Parrinello, A Principled Approach to Enhanced Sampling. doi: 10.26434/chemrxiv.15005686/v1 (2026)](http://dx.doi.org/10.26434/chemrxiv.15005686/v1)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [plumed_ala.dat](./data/plumed_ala.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_ala.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_ala.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [plumed_cal.dat](./data/plumed_cal.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_cal.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_cal.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [plumed_chi.dat](./data/plumed_chi.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_chi.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_chi.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [plumed_sod.dat](./data/plumed_sod.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_sod.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_sod.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [plumed_trp.dat](./data/plumed_trp.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_trp.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_trp.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
  
**Last tested:**  29 Oct 2026, 12:31:37
  
**Project description and instructions**  
The enhanced sampling simulations were performed using Plumed 2.10, gromacs 2024.4, lammps 22 July 2025 The plumed inputs require addtional functionalities developed for this publications. All the extra functions and modified source files are ready to be compiled with plumed mklib.

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=BIASVALUE,PRINT,POSITION,UNITS,CELL,OPES_METAD_EXPLORE,CUSTOM,TORSION,GROUP,DISTANCE,LOAD" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 26 Oct 2026:   
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:26.015" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:26.015](https://www.plumed-nest.org/eggs/26/015/badge.svg)](https://www.plumed-nest.org/eggs/26/015/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/26/015/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/26/015/badge.svg" alt="plumID:26.015"&gt;&lt;/a&gt;</pre>
  </div>
</div>
