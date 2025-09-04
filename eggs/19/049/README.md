**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
**Name:**  Determining the sizes of solid/liquid clusters in MD trajectories of nucleation  
**Archive:** [ https://github.com/gtribello/plumed-inputs/raw/master/Clustering/inputs.zip](https://github.com/gtribello/plumed-inputs/raw/master/Clustering/inputs.zip)  
**Category:**  methods  
**Keywords:**  nucleation, metadynamics, clustering, Steinhardt order parameters  
**Contributor:**  Gareth Tribello  
**Submitted on:** 04 Jun 2019  
**Publication:** [G. A. Tribello, F. Giberti, G. C. Sosso, M. Salvalaglio, M. Parrinello, Analyzing and Driving Cluster Formation in Atomistic Simulations. Journal of Chemical Theory and Computation. 13, 1317–1327 (2017)](http://dx.doi.org/10.1021/acs.jctc.6b01073)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [plumed_GeTe.dat](./data/plumed_GeTe.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_GeTe.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_GeTe.dat.plumed_master.stderr) |  
| [plumed_lj_gas_liquid.dat](./data/plumed_lj_gas_liquid.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/plumed_lj_gas_liquid.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_lj_gas_liquid.dat.plumed_master.stderr) |  
| [plumed_urea.dat](./data/plumed_urea.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/plumed_urea.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_urea.dat.plumed_master.stderr) |  
  
**Last tested:**  04 Sep 2025, 08:36:20
  
**Project description and instructions**  
These are the input files that were used to perform (i) the metadynamics simulations of the vapour liquid transition that is  described in the paper, (ii) the analysis of the urea nucleation trajectories and (iii) the analysis of the GeTe nucleation  trajectories that are described in the paper.

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=LOCAL_Q6,ONES,OUTPUT_CLUSTER,COORDINATIONNUMBER,MORE_THAN,SMAC,METAD,CONTACT_MATRIX,CLUSTER_NATOMS,OUTER_PRODUCT,DISTANCES,CLUSTER_PROPERTIES,MATRIX_VECTOR_PRODUCT,PRINT,DFSCLUSTERING,CLUSTER_DISTRIBUTION,Q6,CUSTOM" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 04 Jun 2019: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:19.049" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:19.049](https://www.plumed-nest.org/eggs/19/049/badge.svg)](https://www.plumed-nest.org/eggs/19/049/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/19/049/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/19/049/badge.svg" alt="plumID:19.049"&gt;&lt;/a&gt;</pre>
  </div>
</div>
