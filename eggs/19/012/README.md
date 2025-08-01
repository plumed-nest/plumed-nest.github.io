**Project ID:** [plumID:19.012]({{ '/' | absolute_url }}eggs/19/012/)  
**Name:**  Martini-Beads multi-scale SAXS  
**Archive:** [ https://zenodo.org/record/6413744/files/paissoni19iucr.zip](https://zenodo.org/record/6413744/files/paissoni19iucr.zip)  
**Category:**  methods  
**Keywords:**  metainference, SAXS, martini, structure refinement, nucleic-acids, protein complex  
**PLUMED version:**  2.6  
**Contributor:**  Carlo Camilloni  
**Submitted on:** 17 Apr 2019  
**Publication:** [C. Paissoni, A. Jussupow, C. Camilloni, Martini bead form factors for nucleic acids and their application in the refinement of protein–nucleic acid complexes against SAXS data. Journal of Applied Crystallography. 52, 394–402 (2019)](http://dx.doi.org/10.1107/S1600576719002450)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [...issoni2019_martiniSAXS/Protein-RNA/plumed-main.dat](./data/paissoni2019_martiniSAXS/Protein-RNA/plumed-main.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/paissoni2019_martiniSAXS/Protein-RNA/plumed-main.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/paissoni2019_martiniSAXS/Protein-RNA/plumed-main.dat.plumed_master.stderr) |  
| [...issoni2019_martiniSAXS/Protein-DNA/plumed-main.dat](./data/paissoni2019_martiniSAXS/Protein-DNA/plumed-main.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/paissoni2019_martiniSAXS/Protein-DNA/plumed-main.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/paissoni2019_martiniSAXS/Protein-DNA/plumed-main.dat.plumed_master.stderr) |  
  
**Last tested:**  25 Jul 2025, 12:02:38
  
**Project description and instructions**  
This is a metainference calculation using SAXS for structure refinement. In particular instead than  calculting SAXS using all the atoms we first maps them on martini beads using CENTER and then we  employ the structure factors parameterised in the paper to efficiently calculate SAXS. The same structure factors can be directly used on Martini simulations

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=ENDPLUMED,INCLUDE,SAXS,RESTRAINT,STATS,UPPER_WALLS,PRINT,WHOLEMOLECULES,DISTANCE,MOLINFO,BIASVALUE,CENTER,GROUP,RMSD" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 17 Apr 2019: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:19.012" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:19.012](https://www.plumed-nest.org/eggs/19/012/badge.svg)](https://www.plumed-nest.org/eggs/19/012/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/19/012/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/19/012/badge.svg" alt="plumID:19.012"&gt;&lt;/a&gt;</pre>
  </div>
</div>
