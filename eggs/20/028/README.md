**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
**Name:**  Well-tempered metadynamics on wt/onc KRas-4B, binding on the anionic membrane  
**Archive:** [ https://github.com/HuixiaLu/well-tempered-metadynamics-on-wt.-onc.-KRas-4B-binding-on-the-anionic-membrane/archive/master.zip](https://github.com/HuixiaLu/well-tempered-metadynamics-on-wt.-onc.-KRas-4B-binding-on-the-anionic-membrane/archive/master.zip) [(browse)](https://github.com/HuixiaLu/well-tempered-metadynamics-on-wt.-onc.-KRas-4B-binding-on-the-anionic-membrane/tree/master)  
**Category:**  bio  
**Keywords:**  metadynamics, KRas-4B, anionic membrane  
**PLUMED version:**  2.5  
**Contributor:**  Huixia Lu  
**Submitted on:** 26 Oct 2020  
**Last revised:** 15 Jan 2021  
**Publication:** [H. Lu, J. Martí, Long-lasting Salt Bridges Provide the Anchoring Mechanism of Oncogenic Kirsten Rat Sarcoma Proteins at Cell Membranes. The Journal of Physical Chemistry Letters. 11, 9938–9945 (2020)](http://dx.doi.org/10.1021/acs.jpclett.0c02809)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [wild-type/plumed-1.dat](./data/wild-type/plumed-1.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/wild-type/plumed-1.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/wild-type/plumed-1.dat.plumed_master.stderr) |  
| [oncogenic/plumed-1.dat](./data/oncogenic/plumed-1.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-failed-red.svg)](data/oncogenic/plumed-1.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/oncogenic/plumed-1.dat.plumed_master.stderr) |  
  
**Last tested:**  25 Jul 2025, 11:54:26
  
**Project description and instructions**  
Use command line 'gmx mdrun -deffnm 800ns-metadynamics -v -plumed plumed-1.dat' to start the metadynamics simulation 

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=METAD,RESTART,FIT_TO_TEMPLATE,PRINT,CENTER,DISTANCE" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 26 Oct 2020: original submission  
**[v2]** 15 Jan 2021: updated doi  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:20.028" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:20.028](https://www.plumed-nest.org/eggs/20/028/badge.svg)](https://www.plumed-nest.org/eggs/20/028/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/20/028/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/20/028/badge.svg" alt="plumID:20.028"&gt;&lt;/a&gt;</pre>
  </div>
</div>
