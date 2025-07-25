**Project ID:** [plumID:25.004]({{ '/' | absolute_url }}eggs/25/004/)  
**Name:**  Machine Learning-Driven Molecular Dynamics Unveil a Bulk Phase Transformation Driving Ammonia Synthesis on Barium Hydride  
**Archive:** [ https://github.com/AxelTG/BaH2/archive/master.zip](https://github.com/AxelTG/BaH2/archive/master.zip) [(browse)](https://github.com/AxelTG/BaH2/tree/master)  
**Category:**  chemistry  
**Keywords:**  OPES, OPES flooding, Catalysis, Ammonia Synthesis  
**PLUMED version:**  2.9  
**Contributor:**  Axel Tosello Gardini  
**Submitted on:** 02 Feb 2025  
**Publication:** unpublished  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [2NH_formation_flooding/plumed.dat](./data/2NH_formation_flooding/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/2NH_formation_flooding/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/2NH_formation_flooding/plumed.dat.plumed_master.stderr) |  
| [H2_flooding/coverage_16.7/plumed.dat](./data/H2_flooding/coverage_16.7/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/H2_flooding/coverage_16.7/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/H2_flooding/coverage_16.7/plumed.dat.plumed_master.stderr) |  
| [H2_flooding/coverage_33.3/plumed.dat](./data/H2_flooding/coverage_33.3/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/H2_flooding/coverage_33.3/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/H2_flooding/coverage_33.3/plumed.dat.plumed_master.stderr) |  
| [H2_flooding/coverage_5.5/plumed.dat](./data/H2_flooding/coverage_5.5/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/H2_flooding/coverage_5.5/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/H2_flooding/coverage_5.5/plumed.dat.plumed_master.stderr) |  
| [H2_flooding/coverage_50/plumed.dat](./data/H2_flooding/coverage_50/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/H2_flooding/coverage_50/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/H2_flooding/coverage_50/plumed.dat.plumed_master.stderr) |  
| [HNNH_formation_flooding/plumed.dat](./data/HNNH_formation_flooding/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/HNNH_formation_flooding/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/HNNH_formation_flooding/plumed.dat.plumed_master.stderr) |  
| [NH2_formation/plumed.dat](./data/NH2_formation/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/NH2_formation/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/NH2_formation/plumed.dat.plumed_master.stderr) |  
| [NH3_formation/plumed.dat](./data/NH3_formation/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/NH3_formation/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/NH3_formation/plumed.dat.plumed_master.stderr) |  
| [NNH_form/700K/plumed.dat](./data/NNH_form/700K/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/NNH_form/700K/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/NNH_form/700K/plumed.dat.plumed_master.stderr) |  
| [NNH_form/plumed.dat](./data/NNH_form/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/NNH_form/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/NNH_form/plumed.dat.plumed_master.stderr) |  
| [NNH_formation_flooding/plumed.dat](./data/NNH_formation_flooding/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/NNH_formation_flooding/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/NNH_formation_flooding/plumed.dat.plumed_master.stderr) |  
  
**Last tested:**  25 Jul 2025, 11:37:36
  
**Project description and instructions**  
It contains the input files necessary to reproduce the results contained here. Simulations were performed in combination with LAMMPS, Deepmd-kit, and CP2K. Please check the README file in each folder of the GitHub repository for more details.

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=DISTANCES,COMMITTOR,PRINT,COORDINATIONNUMBER,UPPER_WALLS,DISTANCE,UNITS,FLUSH,OPES_METAD,CUSTOM,FIXEDATOM,GROUP,ZDISTANCES" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 02 Feb 2025: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:25.004" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:25.004](https://www.plumed-nest.org/eggs/25/004/badge.svg)](https://www.plumed-nest.org/eggs/25/004/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/25/004/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/25/004/badge.svg" alt="plumID:25.004"&gt;&lt;/a&gt;</pre>
  </div>
</div>
