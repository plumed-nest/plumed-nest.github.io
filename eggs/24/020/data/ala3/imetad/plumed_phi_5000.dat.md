**Project ID:** [plumID:24.020]({{ '/' | absolute_url }}eggs/24/020/)  
**Source:** ala3/imetad/plumed_phi_5000.dat  
**Originally used with PLUMED version:** 2.8.1  
**Stable:** [zipped raw stdout](plumed_phi_5000.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_phi_5000.dat.plumed.stderr.txt.zip) - [stderr](plumed_phi_5000.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed_phi_5000.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_phi_5000.dat.plumed_master.stderr.txt.zip) - [stderr](plumed_phi_5000.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/ala3/imetad/plumed_phi_5000.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed_phi_5000.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed_phi_5000.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:blue"># vim:ft=plumed<span class="right">Enables syntax highlighting for PLUMED files in vim. See <a href="https://www.plumed.org/doc-master/user-doc/html/vim">here for more details. </a><i></i></span></span>
<br/><b name="data/ala3/imetad/plumed_phi_5000.datphi-1" onclick='showPath("data/ala3/imetad/plumed_phi_5000.dat","data/ala3/imetad/plumed_phi_5000.datphi-1","data/ala3/imetad/plumed_phi_5000.datphi-1","brown")'>phi-1</b>:   <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=5,7,9,15     
<span style="color:blue" class="comment"># psi-1:   TORSION ATOMS=7,9,15,17    </span>
<span style="display:none;" id="data/ala3/imetad/plumed_phi_5000.datphi-1">The TORSION action with label <b>phi-1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi-1.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/ala3/imetad/plumed_phi_5000.datphi-2" onclick='showPath("data/ala3/imetad/plumed_phi_5000.dat","data/ala3/imetad/plumed_phi_5000.datphi-2","data/ala3/imetad/plumed_phi_5000.datphi-2","brown")'>phi-2</b>:   <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=15,17,19,25  
<span style="color:blue" class="comment"># psi-2:   TORSION ATOMS=17,19,25,27  </span>
<span style="display:none;" id="data/ala3/imetad/plumed_phi_5000.datphi-2">The TORSION action with label <b>phi-2</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi-2.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/ala3/imetad/plumed_phi_5000.datphi-3" onclick='showPath("data/ala3/imetad/plumed_phi_5000.dat","data/ala3/imetad/plumed_phi_5000.datphi-3","data/ala3/imetad/plumed_phi_5000.datphi-3","brown")'>phi-3</b>:   <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=25,27,29,35  
<span style="color:blue" class="comment"># psi-3:   TORSION ATOMS=27,29,35,37  </span>
<br/><span style="display:none;" id="data/ala3/imetad/plumed_phi_5000.datphi-3">The TORSION action with label <b>phi-3</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi-3.value</td><td>the TORSION involving these atoms</td></tr></table></span><span class="plumedtooltip" style="color:green">METAD<span class="right">Used to performed metadynamics on one or more collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/METAD" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/ala3/imetad/plumed_phi_5000.datmtd" onclick='showPath("data/ala3/imetad/plumed_phi_5000.dat","data/ala3/imetad/plumed_phi_5000.datmtd","data/ala3/imetad/plumed_phi_5000.datmtd","brown")'>mtd</b>

  <span class="plumedtooltip">ARG<span class="right">the labels of the scalars on which the bias will act<i></i></span></span>=<b name="data/ala3/imetad/plumed_phi_5000.datphi-1">phi-1</b>,<b name="data/ala3/imetad/plumed_phi_5000.datphi-2">phi-2</b>,<b name="data/ala3/imetad/plumed_phi_5000.datphi-3">phi-3</b>
  <span class="plumedtooltip">PACE<span class="right">the frequency for hill addition<i></i></span></span>=5000
  <span class="plumedtooltip">SIGMA<span class="right">the widths of the Gaussian hills<i></i></span></span>=0.2,0.2,0.2
  <span class="plumedtooltip">HEIGHT<span class="right">the heights of the Gaussian hills<i></i></span></span>=1.65

  <span class="plumedtooltip">BIASFACTOR<span class="right">use well tempered metadynamics and use this bias factor<i></i></span></span>=5
  <span class="plumedtooltip">TEMP<span class="right">the system temperature - this is only needed if you are doing well-tempered metadynamics<i></i></span></span>=400
  <span class="plumedtooltip">GRID_MIN<span class="right">the lower bounds for the grid<i></i></span></span>=-pi,-pi,-pi
  <span class="plumedtooltip">GRID_MAX<span class="right">the upper bounds for the grid<i></i></span></span>=pi,pi,pi
  <span class="plumedtooltip">GRID_BIN<span class="right">the number of bins for the grid<i></i></span></span>=500,500,500
  <span style="color:blue" class="comment"># CALC_RCT</span>
  <span style="color:blue" class="comment"># RCT_USTRIDE=50</span>
  <span class="plumedtooltip">ACCELERATION<span class="right"> Set to TRUE if you want to compute the metadynamics acceleration factor<i></i></span></span>
... METAD
<br/><span style="display:none;" id="data/ala3/imetad/plumed_phi_5000.datmtd">The METAD action with label <b>mtd</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">mtd.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">mtd.acc</td><td>the metadynamics acceleration factor</td></tr></table></span><span class="plumedtooltip" style="color:green">COMMITTOR<span class="right">Does a committor analysis. <a href="https://www.plumed.org/doc-master/user-doc/html/COMMITTOR" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">ARG<span class="right">the labels of the values which is being used to define the committor surface<i></i></span></span>=<b name="data/ala3/imetad/plumed_phi_5000.datphi-1">phi-1</b>,<b name="data/ala3/imetad/plumed_phi_5000.datphi-2">phi-2</b>,<b name="data/ala3/imetad/plumed_phi_5000.datphi-3">phi-3</b>
  <span class="plumedtooltip">BASIN_UL1<span class="right">List of upper limits for basin #<i></i></span></span>=-0.2pi,0.4pi,1.5
  <span class="plumedtooltip">BASIN_LL1<span class="right">List of lower limits for basin #<i></i></span></span>=-0.6pi,0.2pi,0.5
  <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output the reached basin<i></i></span></span>=PASS
... COMMITTOR
<br/><span style="display:none;" id="data/ala3/imetad/plumed_phi_5000.dat">The COMMITTOR action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=<b name="data/ala3/imetad/plumed_phi_5000.datmtd">mtd.bias</b>,<b name="data/ala3/imetad/plumed_phi_5000.datmtd">mtd.acc</b>
  <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=500
  <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=COLVAR
... PRINT
</pre>
{% endraw %}
