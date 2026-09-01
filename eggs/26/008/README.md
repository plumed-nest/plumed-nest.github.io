**Project ID:** [plumID:26.008]({{ '/' | absolute_url }}eggs/26/008/)  
**Name:**  Ensemble Dynamics  
**Archive:** [ https://github.com/Flofega/EnsembleDynamicsPaper/raw/main/plumednest.zip](https://github.com/Flofega/EnsembleDynamicsPaper/raw/main/plumednest.zip)  
**Category:**  methods  
**Keywords:**  State Exploration, Protein Folding, Drug Binding, Phase Transition  
**PLUMED version:**  2.10  
**Contributor:**  Florian M. Dietrich  
**Submitted on:** 09 Jul 2026  
**Publication:** [F. M. Dietrich, M. Parrinello, A Principled Approach to Enhanced Sampling. doi: 10.26434/chemrxiv.15005686/v1 (2026)](http://dx.doi.org/10.26434/chemrxiv.15005686/v1)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [plumed_ala.dat](./data/plumed_ala.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_ala.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_ala.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [plumed_cal.dat](./data/plumed_cal.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_cal.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_cal.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [plumed_chi.dat](./data/plumed_chi.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_chi.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_chi.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [plumed_sod.dat](./data/plumed_sod.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_sod.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_sod.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
| [plumed_trp.dat](./data/plumed_trp.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_trp.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_trp.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
  
**Last tested:**  01 Sep 2026, 14:14:35
  
**Project description and instructions**  
The plumed files all require additional functionality which can be loaded by compiling the included .cpp files. All the plumed inputs expect a torchscript exported model trained with the protocols outlined in the publication and GitHub. The simulations for alanine dipeptide, calixarene, chignolin and trp-cage were performed with GROMACS 2024 patched with Plumed 2.10 and the Sodium simulation with LAMMPS 2025.7.22.3

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=BIASVALUE,OPES_METAD_EXPLORE,PRINT,UNITS,GROUP,LOAD,CELL,DISTANCE,POSITION,CUSTOM,TORSION" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 09 Jul 2026: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:26.008" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:26.008](https://www.plumed-nest.org/eggs/26/008/badge.svg)](https://www.plumed-nest.org/eggs/26/008/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/26/008/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/26/008/badge.svg" alt="plumID:26.008"&gt;&lt;/a&gt;</pre>
  </div>
</div>
