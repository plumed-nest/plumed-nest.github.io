**Project ID:** [plumID:23.010]({{ '/' | absolute_url }}eggs/23/010/)  
**Name:**  An Efficient Metadynamics-Based Protocol To Model the Binding Affinity and the Transition State Ensemble of G‑Protein-Coupled Receptor Ligands  
**Archive:** [ https://github.com/jacquecr23/GPCR-small-ligand-binding-protocol/raw/main/GPCR%20binding%20protocol.zip](https://github.com/jacquecr23/GPCR-small-ligand-binding-protocol/raw/main/GPCR%20binding%20protocol.zip)  
**Category:**  bio  
**Keywords:**  GPCR, binding free energy, free energy surface  
**PLUMED version:**  2.5.3  
**Contributor:**  Timothy Clark  
**Submitted on:** 06 Mar 2023  
**Publication:** [N. Saleh, P. Ibrahim, G. Saladino, F. L. Gervasio, T. Clark, An Efficient Metadynamics-Based Protocol To Model the Binding Affinity and the Transition State Ensemble of G-Protein-Coupled Receptor Ligands. Journal of Chemical Information and Modeling. 57, 1210–1217 (2017)](http://dx.doi.org/10.1021/acs.jcim.6b00772)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [plumed.dat](./data/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/plumed.dat.plumed_master.stderr) |  
  
**Last tested:**  04 Sep 2025, 08:24:44
  
**Project description and instructions**  
Topologies for the receptors were generated using the AMBER99SB-ILDN force field. Ligands were parameterized using the generalized AMBER force field (GAFF) together with AM1-BCC partial charges.
  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=METAD,BIASVALUE,PRINT,CONSTANT,DISTANCE,LOWER_WALLS,WHOLEMOLECULES,MATHEVAL,UPPER_WALLS" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 06 Mar 2023: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:23.010" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:23.010](https://www.plumed-nest.org/eggs/23/010/badge.svg)](https://www.plumed-nest.org/eggs/23/010/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/23/010/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/23/010/badge.svg" alt="plumID:23.010"&gt;&lt;/a&gt;</pre>
  </div>
</div>
