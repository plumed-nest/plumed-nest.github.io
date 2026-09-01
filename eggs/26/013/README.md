**Project ID:** [plumID:26.013]({{ '/' | absolute_url }}eggs/26/013/)  
**Name:**  Characterizing Partially Unfolded States of the C-Terminal Domain in WT and 3PA Mouse Prion Protein  
**Archive:** [ https://zenodo.org/records/22127314/files/PLUMED-NEST-moPrP.zip](https://zenodo.org/records/22127314/files/PLUMED-NEST-moPrP.zip)  
**Category:**  bio  
**Keywords:**  parallel-bias metadynamics, PBMetaD, metadynamics, mouse prion protein, prion protein, protein folding, partially unfolded states, molecular dynamics  
**PLUMED version:**  2.9  
**Contributor:**  Sonali M. Jadhav  
**Submitted on:** 27 Aug 2026  
**Publication:** unpublished  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [3PA/plumed.dat](./data/3PA/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/3PA/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/3PA/plumed.dat.plumed_master.stderr) |  
| [3PA/plumed_cmap.dat](./data/3PA/plumed_cmap.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/3PA/plumed_cmap.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/3PA/plumed_cmap.dat.plumed_master.stderr) |  
| [WT/plumed.dat](./data/WT/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/WT/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/WT/plumed.dat.plumed_master.stderr) |  
| [WT/plumed_cmap.dat](./data/WT/plumed_cmap.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/WT/plumed_cmap.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/WT/plumed_cmap.dat.plumed_master.stderr) |  
  
**Last tested:**  01 Sep 2026, 14:16:14
  
**Project description and instructions**  
The deposited files contain the PLUMED input files and GROMACS input files required to reproduce the parallel-bias metadynamics (PBMetaD) simulations of the WT and 3PA mouse prion protein systems. The simulations were performed using GROMACS 2022.5 and PLUMED 2.9.0, both compiled with MPI support. Each system consists of 20 parallel walkers. For the WT system, execute the simulation from the WT directory. For the 3PA system, execute the simulation from the 3PA directory. The simulations can be run using mpiexec --oversubscribe -np 20 gmx_mpi mdrun -multidir walker1 walker2 walker3 walker4 walker5 walker6 walker7 walker8 walker9 walker10 walker11 walker12 walker13 walker14 walker15 walker16 walker17 walker18 walker19 walker20 -plumed ../plumed.dat -v -ntomp 6. The same command is used for both WT and 3PA, with the command executed from the corresponding WT or 3PA directory. The deposited README file provides the directory structure and additional instructions.

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=GROUP,COORDINATION,ALPHARMSD,GYRATION,DISTANCE,INCLUDE,DUMPMASSCHARGE,MOLINFO,CONTACTMAP,WHOLEMOLECULES,PBMETAD,COM,PRINT" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 27 Aug 2026:   
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:26.013" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:26.013](https://www.plumed-nest.org/eggs/26/013/badge.svg)](https://www.plumed-nest.org/eggs/26/013/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/26/013/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/26/013/badge.svg" alt="plumID:26.013"&gt;&lt;/a&gt;</pre>
  </div>
</div>
