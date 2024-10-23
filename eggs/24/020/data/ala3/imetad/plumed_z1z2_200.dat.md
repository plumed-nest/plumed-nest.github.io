**Project ID:** [plumID:24.020]({{ '/' | absolute_url }}eggs/24/020/)  
**Source:** ala3/imetad/plumed_z1z2_200.dat  
**Originally used with PLUMED version:** 2.8.1  
**Stable:** [zipped raw stdout](plumed_z1z2_200.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_z1z2_200.dat.plumed.stderr.txt.zip) - [stderr](plumed_z1z2_200.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed_z1z2_200.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_z1z2_200.dat.plumed_master.stderr.txt.zip) - [stderr](plumed_z1z2_200.dat.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/ala3/imetad/plumed_z1z2_200.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="plumed_z1z2_200.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="plumed_z1z2_200.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></td></tr><tr><td style="padding:1px"><img src="https://img.shields.io/badge/with-LOAD-yellow.svg" alt="tested on master" /></td></tr>
</table></div></div>
<pre style="width=97%;">
<div class="tooltip" style="color:green">LOAD<div class="right">Loads a library, possibly defining new actions. <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">FILE<div class="right">file to be loaded<i></i></div></div>=Graph.cpp
<br/><span style="display:none;" id="data/ala3/imetad/plumed_z1z2_200.dat">The LOAD action with label <b></b> calculates something</span><b name="data/ala3/imetad/plumed_z1z2_200.datHEAVY" onclick='showPath("data/ala3/imetad/plumed_z1z2_200.dat","data/ala3/imetad/plumed_z1z2_200.datHEAVY","data/ala3/imetad/plumed_z1z2_200.datHEAVY","brown")'>HEAVY</b>: <div class="tooltip" style="color:green">GROUP<div class="right">Define a group of atoms so that a particular list of atoms can be referenced with a single label in definitions of CVs or virtual atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_g_r_o_u_p.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the numerical indexes for the set of atoms in the group<i></i></div></div>=1,5,6,7,9,11,15,16,17,19,21,25,26,27,29,31,35,36,37,39
<br/><span style="display:none;" id="data/ala3/imetad/plumed_z1z2_200.datHEAVY">The GROUP action with label <b>HEAVY</b> calculates something</span><b name="data/ala3/imetad/plumed_z1z2_200.datphi-1" onclick='showPath("data/ala3/imetad/plumed_z1z2_200.dat","data/ala3/imetad/plumed_z1z2_200.datphi-1","data/ala3/imetad/plumed_z1z2_200.datphi-1","brown")'>phi-1</b>:   <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=5,7,9,15       <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<span style="color:blue" class="comment"># psi-1:   TORSION ATOMS=7,9,15,17      NOPBC</span>
<span style="display:none;" id="data/ala3/imetad/plumed_z1z2_200.datphi-1">The TORSION action with label <b>phi-1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi-1.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/ala3/imetad/plumed_z1z2_200.datphi-2" onclick='showPath("data/ala3/imetad/plumed_z1z2_200.dat","data/ala3/imetad/plumed_z1z2_200.datphi-2","data/ala3/imetad/plumed_z1z2_200.datphi-2","brown")'>phi-2</b>:   <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=15,17,19,25    <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<span style="color:blue" class="comment"># psi-2:   TORSION ATOMS=17,19,25,27    NOPBC</span>
<span style="display:none;" id="data/ala3/imetad/plumed_z1z2_200.datphi-2">The TORSION action with label <b>phi-2</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi-2.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/ala3/imetad/plumed_z1z2_200.datphi-3" onclick='showPath("data/ala3/imetad/plumed_z1z2_200.dat","data/ala3/imetad/plumed_z1z2_200.datphi-3","data/ala3/imetad/plumed_z1z2_200.datphi-3","brown")'>phi-3</b>:   <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=25,27,29,35    <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<span style="color:blue" class="comment"># psi-3:   TORSION ATOMS=27,29,35,37    NOPBC</span>
<br/><span style="display:none;" id="data/ala3/imetad/plumed_z1z2_200.datphi-3">The TORSION action with label <b>phi-3</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi-3.value</td><td>the TORSION involving these atoms</td></tr></table></span><div class="tooltip" style="color:green">GRAPH<div class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_a_d.html" style="color:green">More details</a><i></i></div></div> ...
 LABEL=<b name="data/ala3/imetad/plumed_z1z2_200.datmodel" onclick='showPath("data/ala3/imetad/plumed_z1z2_200.dat","data/ala3/imetad/plumed_z1z2_200.datmodel","data/ala3/imetad/plumed_z1z2_200.datmodel","brown")'>model</b>
 ATOMS=<b name="data/ala3/imetad/plumed_z1z2_200.datHEAVY">HEAVY</b>
 RCUT=5.0
 MODEL=model.pt
... GRAPH
<br/><div class="tooltip" style="color:green">METAD<div class="right">Used to performed metadynamics on one or more collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/_m_e_t_a_d.html" style="color:green">More details</a><i></i></div></div> ...
  <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/ala3/imetad/plumed_z1z2_200.datmtd" onclick='showPath("data/ala3/imetad/plumed_z1z2_200.dat","data/ala3/imetad/plumed_z1z2_200.datmtd","data/ala3/imetad/plumed_z1z2_200.datmtd","brown")'>mtd</b>

  <div class="tooltip">ARG<div class="right">the labels of the scalars on which the bias will act<i></i></div></div>=model.node-0,model.node-1
  <div class="tooltip">PACE<div class="right">the frequency for hill addition<i></i></div></div>=200
  <div class="tooltip">SIGMA<div class="right">the widths of the Gaussian hills<i></i></div></div>=0.2,0.2
  <div class="tooltip">HEIGHT<div class="right">the heights of the Gaussian hills<i></i></div></div>=1.65

  <div class="tooltip">BIASFACTOR<div class="right">use well tempered metadynamics and use this bias factor<i></i></div></div>=5
  <div class="tooltip">TEMP<div class="right">the system temperature - this is only needed if you are doing well-tempered metadynamics<i></i></div></div>=400
  <div class="tooltip">GRID_MIN<div class="right">the lower bounds for the grid<i></i></div></div>=-20,-20
  <div class="tooltip">GRID_MAX<div class="right">the upper bounds for the grid<i></i></div></div>=20,15
  <div class="tooltip">GRID_BIN<div class="right">the number of bins for the grid<i></i></div></div>=500,500
  <span style="color:blue" class="comment"># CALC_RCT</span>
  <div class="tooltip">ACCELERATION<div class="right"> Set to TRUE if you want to compute the metadynamics acceleration factor<i></i></div></div>
  <span style="color:blue" class="comment"># RCT_USTRIDE=50</span>
... METAD
<br/><span style="display:none;" id="data/ala3/imetad/plumed_z1z2_200.datmtd">The METAD action with label <b>mtd</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">mtd.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">mtd.acc</td><td>the metadynamics acceleration factor</td></tr></table></span><div class="tooltip" style="color:green">COMMITTOR<div class="right">Does a committor analysis. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_m_m_i_t_t_o_r.html" style="color:green">More details</a><i></i></div></div> ...
  <div class="tooltip">ARG<div class="right">the labels of the values which is being used to define the committor surface<i></i></div></div>=<b name="data/ala3/imetad/plumed_z1z2_200.datphi-1">phi-1</b>,<b name="data/ala3/imetad/plumed_z1z2_200.datphi-2">phi-2</b>,<b name="data/ala3/imetad/plumed_z1z2_200.datphi-3">phi-3</b>
  <div class="tooltip">BASIN_UL1<div class="right">List of upper limits for basin #<i></i></div></div>=-0.2pi,0.4pi,1.5
  <div class="tooltip">BASIN_LL1<div class="right">List of lower limits for basin #<i></i></div></div>=-0.6pi,0.2pi,0.5
  <div class="tooltip">FILE<div class="right">the name of the file on which to output the reached basin<i></i></div></div>=PASS
... COMMITTOR
<br/><div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> ...
  <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=<b name="data/ala3/imetad/plumed_z1z2_200.datmtd">mtd.bias</b>,<b name="data/ala3/imetad/plumed_z1z2_200.datmtd">mtd.acc</b>
  <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=500
  <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=COLVAR
... PRINT
</pre>
{% endraw %}
