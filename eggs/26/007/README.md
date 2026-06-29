**Project ID:** [plumID:26.007]({{ '/' | absolute_url }}eggs/26/007/)  
**Name:**  Metadynamics Simulations Reveal the Protonation-Dependent Conformational Landscape of GSK-3β Dual Inhibitors  
**Archive:** [ https://github.com/gmelisi/GSK-3b_METAD/raw/main/GSK3b_METAD.zip](https://github.com/gmelisi/GSK-3b_METAD/raw/main/GSK3b_METAD.zip)  
**Category:**  chemistry  
**Keywords:**  metadynamics, ligand unbinding, path CVs, funnel metadynamics  
**PLUMED version:**  2.9  
**Contributor:**  Gian Marco Elisi  
**Submitted on:** 23 Jun 2026  
**Publication:** unpublished  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [fun_metad/plumed_metad_pcv_funnel_switch.dat](./data/fun_metad/plumed_metad_pcv_funnel_switch.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/fun_metad/plumed_metad_pcv_funnel_switch.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/fun_metad/plumed_metad_pcv_funnel_switch.dat.plumed_master.stderr) |  
| [pcv_metad/plumed_metad_pcv.dat](./data/pcv_metad/plumed_metad_pcv.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/pcv_metad/plumed_metad_pcv.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/pcv_metad/plumed_metad_pcv.dat.plumed_master.stderr) |  
  
**Last tested:**  29 Jun 2026, 10:06:15
  
**Project description and instructions**  
Input files for GROMACS and PLUMED to perform Path Collective Variables (PCVs) and Funnel Metadynamics simulations of the GSK-3β complex with a phenyl-piperazine derivative, including topology, MD parameters and coordinates, and structural templates for PBC treatment, definition of PCVs and restraint application.

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=DISTANCE,FUNNEL_PS,FUNNEL,UNITS,WHOLEMOLECULES,COM,MATHEVAL,UPPER_WALLS,ANGLE,ENDPLUMED,METAD,MOLINFO,PRINT,LOWER_WALLS,COMBINE,RMSD,PATHMSD" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 23 Jun 2026: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:26.007" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:26.007](https://www.plumed-nest.org/eggs/26/007/badge.svg)](https://www.plumed-nest.org/eggs/26/007/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/26/007/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/26/007/badge.svg" alt="plumID:26.007"&gt;&lt;/a&gt;</pre>
  </div>
</div>
