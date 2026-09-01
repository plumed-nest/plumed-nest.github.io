**Project ID:** [plumID:26.014]({{ '/' | absolute_url }}eggs/26/014/)  
**Name:**  Dissociation free energy (DFE) calculationsfor GPR15L–polySia  
**Archive:** [ https://github.com/gcourtade/papers/raw/master/2026/GPR15L_polySia/plumed_nest.zip](https://github.com/gcourtade/papers/raw/master/2026/GPR15L_polySia/plumed_nest.zip)  
**Category:**  bio  
**Keywords:**  metadynamics, protein-carbohydrate interaction  
**PLUMED version:**  2.8.3  
**Contributor:**  Davide Luciano and Gaston Courtade  
**Submitted on:** 01 Sep 2026  
**Publication:** unpublished  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [DP10/plumed.dat](./data/DP10/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/DP10/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/DP10/plumed.dat.plumed_master.stderr) |  
| [DP20/plumed.dat](./data/DP20/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/DP20/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/DP20/plumed.dat.plumed_master.stderr) |  
| [DP5/plumed.dat](./data/DP5/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/DP5/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/DP5/plumed.dat.plumed_master.stderr) |  
  
**Last tested:**  01 Sep 2026, 14:14:08
  
**Project description and instructions**  
1) build solvated, neutralized system (see unbiased_run.sh header) with editconf -> solvate -> genion -> emin.mdp. 2) one long unbiased reference trajectory with ./unbiased_run.sh (slurm job; grompp mdp/{nvt,npt,md}.mdp then mdrun). 3) metadynamics replica ensemble with ./run.sh (regenerates plumed.dat, loops rep_i with seeded velocities; grompp nvt_seeded.mdp -> npt.mdp -> md_short.mdp + plumed). `run.sh` writes `plumed.dat` itself and is self-contained apart from cluster environment variables (`$gmx`, `$plumed`, `PLUMED_KERNEL`) — adjust the paths at the top for your installation. Seeds are derived from `BASE_SEED` to make the ensemble reproducible. 

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=PRINT,METAD,DISTANCE,UPPER_WALLS,COM,GROUP" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 01 Sep 2026:   
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:26.014" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:26.014](https://www.plumed-nest.org/eggs/26/014/badge.svg)](https://www.plumed-nest.org/eggs/26/014/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/26/014/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/26/014/badge.svg" alt="plumID:26.014"&gt;&lt;/a&gt;</pre>
  </div>
</div>
