**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
**Name:**  Substrate recognition and catalysis by glycosaminoglycan sulfotransferases  
**Archive:** [ https://github.com/tarsisferreira/Substrate-recognition-and-catalysis-by-glycosaminoglycan-sulfotransferases/archive/main.zip](https://github.com/tarsisferreira/Substrate-recognition-and-catalysis-by-glycosaminoglycan-sulfotransferases/archive/main.zip) [(browse)](https://github.com/tarsisferreira/Substrate-recognition-and-catalysis-by-glycosaminoglycan-sulfotransferases/tree/main)  
**Category:**  bio  
**Keywords:**  metadynamics, well-tempered metadynamics, puckering, coordination  
**PLUMED version:**  2.4  
**Contributor:**  Tarsis Ferreira  
**Submitted on:** 04 Jan 2021  
**Publication:** [T. F. Gesteira, T. D. Marforio, J. W. Mueller, M. Calvaresi, V. J. Coulson-Thomas, Structural Determinants of Substrate Recognition and Catalysis by Heparan Sulfate Sulfotransferases. ACS Catalysis. 11, 10974–10987 (2021)](http://dx.doi.org/10.1021/acscatal.1c03088)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [HS2ST/plumed.dat](./data/HS2ST/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/HS2ST/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/HS2ST/plumed.dat.plumed_master.stderr) |  
| [HS6ST/plumed.dat](./data/HS6ST/plumed.dat.md) |  [![tested on v2.10](https://img.shields.io/badge/v2.10-passing-green.svg)](data/HS6ST/plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-failed-red.svg)](data/HS6ST/plumed.dat.plumed_master.stderr) |  
  
**Last tested:**  25 Jul 2025, 11:52:11
  
**Project description and instructions**  
These are the input files used to converge the puckering free energy landscapes of the acceptor uronic acid of the chicken 2-o-sulfotransferase (PDB code 4NDZ) and the water coordination around the catalytic histidine of the zebrafish 6-o-sulfotransferase. The input files were used with amber16 and PLUMED 2.3.8 for calculating the puckering metadynamics and GROMACS 2018.3 and PLUMED 2.4.2. 

  
{% raw %}
<b><a href="https://www.plumed.org/doc-master/user-doc/html/actionlist/?actions=WHOLEMOLECULES,REWEIGHT_METAD,GROUP,DUMPGRID,UPPER_WALLS,PUCKERING,ENERGY,DISTANCE,MOLINFO,HISTOGRAM,RANDOM_EXCHANGES,METAD,COORDINATION,LOWER_WALLS,INCLUDE,PRINT" target="_blank">Click here</a> to open manual pages for actions used in this project.</b>
{% endraw %}
**Submission history**  
**[v1]** 04 Jan 2021: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:21.001" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:21.001](https://www.plumed-nest.org/eggs/21/001/badge.svg)](https://www.plumed-nest.org/eggs/21/001/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/21/001/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/21/001/badge.svg" alt="plumID:21.001"&gt;&lt;/a&gt;</pre>
  </div>
</div>
