**Project ID:** [plumID:19.057]({{ '/' | absolute_url }}eggs/19/057/)  
**Name:**  SAXS ensembles using Martini-Beads multi-scale SAXS  
**Archive:** [ https://zenodo.org/records/10878367/files/diubq_k63.zip](https://zenodo.org/records/10878367/files/diubq_k63.zip)  
**Category:**  methods  
**Keywords:**  metainference, SAXS, martini, ensemble determination, metadynamics, protein dynamics  
**PLUMED version:**  2.6  
**Contributor:**  Cristina Paissoni  
**Submitted on:** 03 Jul 2019  
**Last revised:** 26 Mar 2024  
**Publication:** [C. Paissoni, A. Jussupow, C. Camilloni, Determination of Protein Structural Ensembles by Hybrid-Resolution SAXS Restrained Molecular Dynamics. Journal of Chemical Theory and Computation. 16, 2825–2834 (2020)](http://dx.doi.org/10.1021/acs.jctc.9b01181)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [diubq_k63/plumed-main.dat](./data/diubq_k63/plumed-main.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/diubq_k63/plumed-main.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/diubq_k63/plumed-main.dat.plumed_master.stderr) |  
  
**Last tested:**  04 Sep 2025, 08:36:03
  
**Project description and instructions**  
this is a metadynamics metainference calculation using SAXS for protein structural ensemble determination. Simulations can be run using GROMACS 2018.x and PLUMED-ISDB. This uses multiple replica simulations i.e. -multidir  

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=CENTER,BIASVALUE,WHOLEMOLECULES,ENDPLUMED,ANGLE,INCLUDE,COORDINATION,MATHEVAL,MOLINFO,ALPHABETA,ENSEMBLE,STATS,SAXS,PRINT,COMBINE,PBMETAD,GROUP" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 03 Jul 2019: original submission  
**[v2]** 23 May 2020: updated doi  
**[v3]** 26 Mar 2024: fixed to keep the input compatible with newest plumed  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:19.057" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:19.057](https://www.plumed-nest.org/eggs/19/057/badge.svg)](https://www.plumed-nest.org/eggs/19/057/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/19/057/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/19/057/badge.svg" alt="plumID:19.057"&gt;&lt;/a&gt;</pre>
  </div>
</div>
