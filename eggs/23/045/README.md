**Project ID:** [plumID:23.045]({{ '/' | absolute_url }}eggs/23/045/)  
**Name:**  Minute-timescale simulations of G Protein Coupled Receptor A2A activation mechanism reveal a receptor pseudo-active state  
**Archive:** [ https://github.com/vmdamore/A2AR-Activation-Simulations/archive/refs/heads/main.zip](https://github.com/vmdamore/A2AR-Activation-Simulations/archive/refs/heads/main.zip)  
**Category:**  bio  
**Keywords:**  Path CVs Metadynamics, GPCRs activation transition  
**PLUMED version:**  2.7.1  
**Contributor:**  Vittorio Limongelli  
**Submitted on:** 16 Nov 2023  
**Last revised:** 13 Jul 2025  
**Publication:** [V. M. D’Amore, P. Conflitti, L. Marinelli, V. Limongelli, Minute-timescale free-energy calculations reveal a pseudo-active state in the adenosine A2A receptor activation mechanism. Chem. 10, 3678–3698 (2024)](http://dx.doi.org/10.1016/j.chempr.2024.08.004)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [Path-CVs_MetaD/apo/plumed.dat](./data/Path-CVs_MetaD/apo/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/Path-CVs_MetaD/apo/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/Path-CVs_MetaD/apo/plumed.dat.plumed_master.stderr) |  
| [Path-CVs_MetaD/neca-bound/plumed.dat](./data/Path-CVs_MetaD/neca-bound/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/Path-CVs_MetaD/neca-bound/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/Path-CVs_MetaD/neca-bound/plumed.dat.plumed_master.stderr) |  
| [Path-CVs_MetaD/zma-bound/plumed.dat](./data/Path-CVs_MetaD/zma-bound/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/Path-CVs_MetaD/zma-bound/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/Path-CVs_MetaD/zma-bound/plumed.dat.plumed_master.stderr) |  
  
**Last tested:**  04 Sep 2025, 08:09:44
  
**Project description and instructions**  
Input files (input structures, topology, PLUMED input) for simulations used to investigate the activation mechanism of A2A receptor. The simulations were performed with Gromacs 2020.6 version patched with Plumed 2.7.1
  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=MOLINFO,METAD,ALPHARMSD,DISTANCE,PRINT,CONTACTMAP,FUNCPATHMSD,UPPER_WALLS,INCLUDE,PATHMSD,LOWER_WALLS" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 16 Nov 2023: original submission  
**[v2]** 13 Jul 2025: updated reference  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:23.045" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:23.045](https://www.plumed-nest.org/eggs/23/045/badge.svg)](https://www.plumed-nest.org/eggs/23/045/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/23/045/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/23/045/badge.svg" alt="plumID:23.045"&gt;&lt;/a&gt;</pre>
  </div>
</div>
