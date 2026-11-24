**Project ID:** [plumID:26.018]({{ '/' | absolute_url }}eggs/26/018/)  
**Name:**  d-SEAMS cage counts  
**Archive:** [ https://github.com/d-SEAMS/dseams-plumed/releases/download/v0.4.1/dseams-plumed-v0.4.1-nest.zip](https://github.com/d-SEAMS/dseams-plumed/releases/download/v0.4.1/dseams-plumed-v0.4.1-nest.zip)  
**Category:**  methods  
**Keywords:**  ice, nucleation, cages, CHILL+, hydrate, brine, topology  
**PLUMED version:**  2.9  
**Contributor:**  Rohit Goswami  
**Submitted on:** 17 Nov 2026  
**Publication:** [R. Goswami, A. Goswami, J. K. Singh, d-SEAMS: Deferred Structural Elucidation Analysis for Molecular Simulations. Journal of Chemical Information and Modeling 60, 2169–2177 (2020)](http://dx.doi.org/10.1021/acs.jcim.0c00031)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [plumed.dat](./data/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/plumed.dat.plumed_master.stderr) [![with LOAD](https://img.shields.io/badge/with-LOAD-yellow.svg)]({{ "/" | absolute_url }}badges) |  
  
**Last tested:**  24 Nov 2026, 19:06:25
  
**Project description and instructions**  
DSEAMS_CAGES is the d-SEAMS topological ice score as a PLUMED action with no derivatives. The three actions in plumed.dat score ice nucleation, a brine front, and the filled cages of a methane hydrate. PLUMED 2.9 or later. Build libdseams_plumed.so from [here](https://github.com/d-SEAMS/dseams-plumed) at tag v0.4.0 against seams-core v2.14.0.

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=LOAD,UNITS,PRINT" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 17 Nov 2026:   
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:26.018" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:26.018](https://www.plumed-nest.org/eggs/26/018/badge.svg)](https://www.plumed-nest.org/eggs/26/018/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/26/018/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/26/018/badge.svg" alt="plumID:26.018"&gt;&lt;/a&gt;</pre>
  </div>
</div>
