**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
**Name:**  Colloid Crystallisation Analyses  
**Archive:** [ https://github.com/aaronrfinney/VAMP-MSM/raw/main/PLUMED-driver.zip](https://github.com/aaronrfinney/VAMP-MSM/raw/main/PLUMED-driver.zip)  
**Category:**  materials  
**Keywords:**  Q4, Q6, Pair Entropy, DFS  
**PLUMED version:**  2.7.2  
**Contributor:**  Aaron Finney  
**Submitted on:** 21 Dec 2022  
**Publication:** [A. R. Finney, M. Salvalaglio, A variational approach to assess reaction coordinates for two-step crystallization. The Journal of Chemical Physics. 158 (2023)](http://dx.doi.org/10.1063/5.0139842)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [plumed-all-search.dat](./data/plumed-all-search.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed-all-search.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed-all-search.dat.plumed_master.stderr) |  
  
**Last tested:**  03 Feb 2026, 21:16:43
  
**Project description and instructions**  
The input file is designed to be executed using the driver to post-process LAMMPS simulation trajectories and compute a range of CVs used in Variational Analysis of Markov Processes (VAMP) and to construct Bayesian Markov State Models (MSMs). Run the driver using e.g. `plumed driver --ixyz dump.3Dcolloid.xyz --plumed plumed-all-search.dat --timestep 1 --trajectory-stride 1 --box 92.83178,92.83178,92.83178`.

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=PRINT,Q6,LOCAL_AVERAGE,DFSCLUSTERING,CONTACT_MATRIX,Q4,MFILTER_LESS,LOCAL_Q4,CLUSTER_NATOMS,COMBINE,LOCAL_Q6,COORDINATIONNUMBER,MFILTER_MORE,GROUP" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 21 Dec 2022: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:22.044" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:22.044](https://www.plumed-nest.org/eggs/22/044/badge.svg)](https://www.plumed-nest.org/eggs/22/044/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/22/044/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/22/044/badge.svg" alt="plumID:22.044"&gt;&lt;/a&gt;</pre>
  </div>
</div>
