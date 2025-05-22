**Project ID:** [plumID:25.008]({{ '/' | absolute_url }}eggs/25/008/)  
**Name:**  Deep TICA CV from Nonequilibrium Metadynamics using Koopman Reweighting  
**Archive:** [ https://github.com/dhimanray/Nonequilibrium_DeepTICA/archive/main.zip](https://github.com/dhimanray/Nonequilibrium_DeepTICA/archive/main.zip) [(browse)](https://github.com/dhimanray/Nonequilibrium_DeepTICA/tree/main)  
**Category:**  methods  
**Keywords:**  metadynamics, OPES, Machine Learning CV, PyTorch, Koopman Reweighting  
**PLUMED version:**  2.10  
**Contributor:**  Dhiman Ray  
**Submitted on:** 18 Mar 2025  
**Publication:** [J. Hanni, D. Ray, Data Efficient Learning of Molecular Slow Modes from Nonequilibrium Metadynamics (2025)](http://dx.doi.org/10.26434/chemrxiv-2025-vswkj)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [ala2/opes/plumed.dat](./data/ala2/opes/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/ala2/opes/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/ala2/opes/plumed.dat.plumed_master.stderr) |  
| [ala2/training/metad_for_training/plumed.dat](./data/ala2/training/metad_for_training/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/ala2/training/metad_for_training/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/ala2/training/metad_for_training/plumed.dat.plumed_master.stderr) |  
| [chignolin/opes/plumed.dat](./data/chignolin/opes/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/chignolin/opes/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/chignolin/opes/plumed.dat.plumed_master.stderr) |  
| [chignolin/training/metad_for_training/plumed.dat](./data/chignolin/training/metad_for_training/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/chignolin/training/metad_for_training/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/chignolin/training/metad_for_training/plumed.dat.plumed_master.stderr) |  
| [...aining/metad_for_training/plumed_ca_descriptor.dat](./data/chignolin/training/metad_for_training/plumed_ca_descriptor.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/chignolin/training/metad_for_training/plumed_ca_descriptor.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/chignolin/training/metad_for_training/plumed_ca_descriptor.dat.plumed_master.stderr) |  
| [mueller/opes/plumed.dat](./data/mueller/opes/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/mueller/opes/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/mueller/opes/plumed.dat.plumed_master.stderr) |  
| [mueller/opes/plumed_no_metad_bias.dat](./data/mueller/opes/plumed_no_metad_bias.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/mueller/opes/plumed_no_metad_bias.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/mueller/opes/plumed_no_metad_bias.dat.plumed_master.stderr) |  
| [mueller/training/metad_for_training/plumed.dat](./data/mueller/training/metad_for_training/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/mueller/training/metad_for_training/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/mueller/training/metad_for_training/plumed.dat.plumed_master.stderr) |  
  
**Last tested:**  22 May 2025, 18:05:20
  
**Project description and instructions**  
All simulations were performed using the PLUMED-PyTorch interface patched with GROMACS 2024.3. 

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=GROUP,OPES_METAD,UPPER_WALLS,POSITION,WHOLEMOLECULES,CUSTOM,PRINT,TORSION,ENERGY,RMSD,LOWER_WALLS,UNITS,BIASVALUE,METAD,ENDPLUMED,DISTANCE,PYTORCH_MODEL,MOLINFO" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 18 Mar 2025: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:25.008" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:25.008](https://www.plumed-nest.org/eggs/25/008/badge.svg)](https://www.plumed-nest.org/eggs/25/008/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/25/008/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/25/008/badge.svg" alt="plumID:25.008"&gt;&lt;/a&gt;</pre>
  </div>
</div>
