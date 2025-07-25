**Project ID:** [plumID:20.018]({{ '/' | absolute_url }}eggs/20/018/)  
**Name:**  Free energy barriers from biased molecular dynamics simulations  
**Archive:** [ https://github.com/kbal/fesbarrier/archive/main.zip](https://github.com/kbal/fesbarrier/archive/main.zip) [(browse)](https://github.com/kbal/fesbarrier/tree/main)  
**Category:**  methods  
**Keywords:**  kinetics, free energy barriers, chemical reactions, nucleation, metadynamics  
**PLUMED version:**  2.6-mod  
**Contributor:**  Kristof Bal  
**Submitted on:** 24 Jun 2020  
**Last revised:** 02 Dec 2020  
**Publication:** [K. M. Bal, S. Fukuhara, Y. Shibuta, E. C. Neyts, Free energy barriers from biased molecular dynamics simulations. The Journal of Chemical Physics. 153 (2020)](http://dx.doi.org/10.1063/5.0020240)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [da-tt/plumed.inp](./data/da-tt/plumed.inp.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/da-tt/plumed.inp.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/da-tt/plumed.inp.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) [![with custom code](https://img.shields.io/badge/with-custom_code-red.svg)]({{ "/" | absolute_url }}badges) |  
| [da-wt/plumed.inp](./data/da-wt/plumed.inp.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/da-wt/plumed.inp.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/da-wt/plumed.inp.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) [![with custom code](https://img.shields.io/badge/with-custom_code-red.svg)]({{ "/" | absolute_url }}badges) |  
| [dimer/plumed.inp](./data/dimer/plumed.inp.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/dimer/plumed.inp.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/dimer/plumed.inp.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) [![with custom code](https://img.shields.io/badge/with-custom_code-red.svg)]({{ "/" | absolute_url }}badges) |  
| [na/plumed.inp](./data/na/plumed.inp.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/na/plumed.inp.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/na/plumed.inp.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) [![with custom code](https://img.shields.io/badge/with-custom_code-red.svg)]({{ "/" | absolute_url }}badges) |  
  
**Last tested:**  25 Jul 2025, 11:48:49
  
**Project description and instructions**  
Used with a recent LAMMPS snapshot and CP2K 7.1. A representative PLUMED input for each system or setup is provided. Extra codes are included. Matching LAMMPS and CP2K inputs are also provided. 

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=PAIRENTROPY,UPPER_WALLS,REWEIGHT_BIAS,DENSITY,COORDINATIONNUMBER,REWEIGHT_METAD,COMBINE,SPRINT,LOWER_WALLS,PRINT,ENERGY,Q6,VOLUME,LOAD,FLUSH,METAD,CENTER,DUMPGRID,HISTOGRAM,UNITS,DISTANCE,CONTACT_MATRIX,COORDINATION,CONVERT_TO_FES,LOCAL_AVERAGE" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 24 Jun 2020: original submission  
**[v2]** 23 Sep 2020: updated doi  
**[v3]** 02 Dec 2020: fixed file links  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:20.018" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:20.018](https://www.plumed-nest.org/eggs/20/018/badge.svg)](https://www.plumed-nest.org/eggs/20/018/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/20/018/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/20/018/badge.svg" alt="plumID:20.018"&gt;&lt;/a&gt;</pre>
  </div>
</div>
