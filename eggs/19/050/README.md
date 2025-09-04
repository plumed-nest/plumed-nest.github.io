**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
**Name:**  Using intrinsic surface to calculate the free energy change when nanoparticles adsorb on membranes  
**Archive:** [ https://github.com/gtribello/plumed-inputs/raw/master/Membranes/inputs.zip](https://github.com/gtribello/plumed-inputs/raw/master/Membranes/inputs.zip)  
**Category:**  chemistry  
**Keywords:**  metadynamics, membranes, Willard Chandler surface  
**Contributor:**  Gareth Tribello  
**Submitted on:** 04 Jun 2019  
**Publication:** [J. Klug, C. Triguero, M. G. Del Pópolo, G. A. Tribello, Using Intrinsic Surfaces To Calculate the Free-Energy Change When Nanoparticles Adsorb on Membranes. The Journal of Physical Chemistry B. 122, 6417–6422 (2018)](http://dx.doi.org/10.1021/acs.jpcb.8b03661)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [plumed_histogram.dat](./data/plumed_histogram.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/plumed_histogram.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/plumed_histogram.dat.plumed_master.stderr) |  
| [plumed_metad.dat](./data/plumed_metad.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/plumed_metad.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/plumed_metad.dat.plumed_master.stderr) |  
| [plumed_reweight.dat](./data/plumed_reweight.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/plumed_reweight.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/plumed_reweight.dat.plumed_master.stderr) |  
  
**Last tested:**  04 Sep 2025, 08:38:22
  
**Project description and instructions**  
The input files were used to perform a metadynamics simulation in which a nanoparticle was forced to adsorb and desorb from a membrane surface.  The free energy as a function of the distance between the nanoparticle and the surface was computed. As discussed in the attached article  molecular dynamics simulations were performed using GROMACS 5 and the non-polarizable MARTINI model.

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=DUMPGRID,METAD,RESTART,PRINT,CONVERT_TO_FES,READ,HISTOGRAM,DISTANCE_FROM_CONTOUR,COMBINE,REWEIGHT_BIAS,UPPER_WALLS" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 04 Jun 2019: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:19.050" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:19.050](https://www.plumed-nest.org/eggs/19/050/badge.svg)](https://www.plumed-nest.org/eggs/19/050/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/19/050/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/19/050/badge.svg" alt="plumID:19.050"&gt;&lt;/a&gt;</pre>
  </div>
</div>
