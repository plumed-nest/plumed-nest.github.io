**Project ID:** [plumID:19.009]({{ '/' | absolute_url }}eggs/19/009/)  
**Name:**  RNA tetraloops folding  
**Archive:** [ https://github.com/srnas/tetraloops-trajectories/archive/d54b27a82ab828f4f7a2c168c2c8c8f02d08ce09.zip](https://github.com/srnas/tetraloops-trajectories/archive/d54b27a82ab828f4f7a2c168c2c8c8f02d08ce09.zip) [(browse)](https://github.com/srnas/tetraloops-trajectories/tree/d54b27a82ab828f4f7a2c168c2c8c8f02d08ce09)  
**Checksum (md5):** 752da87e6f72a8f2cfe5aded0ed42bfd  
**Category:**  bio  
**Keywords:**  metadynamics, RNA, folding  
**PLUMED version:**  2.4  
**Contributor:**  Giovanni Bussi  
**Submitted on:** 16 Apr 2019  
**Publication:** [S. Bottaro, P. Banáš, J. Šponer, G. Bussi, Free Energy Landscape of GAGA and UUCG RNA Tetraloops, The Journal of Physical Chemistry Letters 7, 4032–4038 (2016)](http://dx.doi.org/10.1021/acs.jpclett.6b01905)  
  
**PLUMED input files**  
  
| File     | Compatible with |  
|:--------:|:--------:|  
| [GAGA/ccGAGAgg.plumed.dat](./data/GAGA/ccGAGAgg.plumed.dat.md) |  [![tested on v2.7](https://img.shields.io/badge/v2.7-passing-green.svg)](data/GAGA/ccGAGAgg.plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/GAGA/ccGAGAgg.plumed.dat.plumed_master.stderr) |  
| [UUCG/ccUUCGgg.plumed.dat](./data/UUCG/ccUUCGgg.plumed.dat.md) |  [![tested on v2.7](https://img.shields.io/badge/v2.7-passing-green.svg)](data/UUCG/ccUUCGgg.plumed.dat.plumed.stderr) [![tested on master](https://img.shields.io/badge/master-passing-green.svg)](data/UUCG/ccUUCGgg.plumed.dat.plumed_master.stderr) |  
  
**Last tested:**  11 Jan 2021, 22:54:06
  
**Project description and instructions**  
The zip files contains the trajectories discussed in the paper as well as a couple of plumed input files that were used for analysis. In order to run the metadynamics simulations described in the paper one should fix the metadynamics parameters (height and pace). In addition, histograms were computed using a syntax that changed in PLUMED 2.4. To use them with a more recent PLUMED they should be updated.

  
**Submission history**  
**[v1]** 16 Apr 2019: original submission  
  
**Badge**  
Click on the image below and get the code to add the badge to your website!  
<img src="./badge.svg" alt="plumeDnest:19.009" id="myBtn" class="badge">
<div id="myModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    Markdown<pre>[![plumID:19.009](https://www.plumed-nest.org/eggs/19/009/badge.svg)](https://www.plumed-nest.org/eggs/19/009/)</pre>
    HTML<pre>&lt;a href="https://www.plumed-nest.org/eggs/19/009/"&gt;&lt;img src="https://www.plumed-nest.org/eggs/19/009/badge.svg" alt="plumID:19.009"&gt;&lt;/a&gt;</pre>
  </div>
</div>
