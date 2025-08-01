**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
**Name:**  MD SAXS GTPase associated center  
**Archive:** [ https://github.com/bussilab/saxs-md-gac/archive/24f5aa860bf1b3c6eb2062a5137999dba082561d.zip](https://github.com/bussilab/saxs-md-gac/archive/24f5aa860bf1b3c6eb2062a5137999dba082561d.zip) [(browse)](https://github.com/bussilab/saxs-md-gac/tree/24f5aa860bf1b3c6eb2062a5137999dba082561d)  
**Category:**  bio  
**Keywords:**  metadynamics, RNA, folding, SAXS  
**PLUMED version:**  2.5  
**Contributor:**  Giovanni Bussi  
**Submitted on:** 19 Apr 2021  
**Last revised:** 03 Apr 2022  
**Publication:** [M. Bernetti, K. B. Hall, G. Bussi, Reweighting of molecular simulations with explicit-solvent SAXS restraints elucidates ion-dependent RNA ensembles. Nucleic Acids Research. 49, e84–e84 (2021)](http://dx.doi.org/10.1093/nar/gkab459)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [input_files/plumed.dat](./data/input_files/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/input_files/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/input_files/plumed.dat.plumed_master.stderr) |  
  
**Last tested:**  25 Jul 2025, 11:48:14
  
**Project description and instructions**  
The included input file has been adapted to be compatible with v2.7. In particular, SAXS components are labeled as `saxs_bias.q-0` instead of `saxs_bias.q_0`.

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=INCLUDE,GYRATION,MOLINFO,LOWER_WALLS,ERMSD,PRINT,CUSTOM,GROUP,SAXS,UPPER_WALLS,WHOLEMOLECULES,METAD" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 19 Apr 2021: original submission  
**[v2]** 14 Jun 2021: added DOI  
**[v3]** 03 Apr 2022: fixed input for plumed 2.8  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:21.016" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:21.016](https://www.plumed-nest.org/eggs/21/016/badge.svg)](https://www.plumed-nest.org/eggs/21/016/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/21/016/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/21/016/badge.svg" alt="plumID:21.016"&gt;&lt;/a&gt;</pre>
  </div>
</div>
