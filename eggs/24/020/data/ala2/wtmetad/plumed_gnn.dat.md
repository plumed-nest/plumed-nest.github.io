**Project ID:** [plumID:24.020]({{ '/' | absolute_url }}eggs/24/020/)  
**Source:** ala2/wtmetad/plumed_gnn.dat  
**Originally used with PLUMED version:** 2.8.1  
**Stable:** [zipped raw stdout](plumed_gnn.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_gnn.dat.plumed.stderr.txt.zip) - [stderr](plumed_gnn.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed_gnn.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_gnn.dat.plumed_master.stderr.txt.zip) - [stderr](plumed_gnn.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/ala2/wtmetad/plumed_gnn.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed_gnn.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed_gnn.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></div>
<div class="headerBadge"><img src="https://img.shields.io/badge/with-LOAD-yellow.svg" alt="tested on master" /></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:green">LOAD<span class="right">Loads a library, possibly defining new actions. <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FILE<span class="right">file to be loaded<i></i></span></span>=Graph.cpp

<span style="color:blue" class="comment"># Calculate the collective variables</span>
<span style="display:none;" id="data/ala2/wtmetad/plumed_gnn.dat">The LOAD action with label <b></b> calculates something</span><b name="data/ala2/wtmetad/plumed_gnn.datHEAVY" onclick='showPath("data/ala2/wtmetad/plumed_gnn.dat","data/ala2/wtmetad/plumed_gnn.datHEAVY","data/ala2/wtmetad/plumed_gnn.datHEAVY","brown")'>HEAVY</b>: <span class="plumedtooltip" style="color:green">GROUP<span class="right">Define a group of atoms so that a particular list of atoms can be referenced with a single label in definitions of CVs or virtual atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/GROUP" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the numerical indexes for the set of atoms in the group<i></i></span></span>=2,5,6,7,9,11,15,16,17,19

<span style="display:none;" id="data/ala2/wtmetad/plumed_gnn.datHEAVY">The GROUP action with label <b>HEAVY</b> calculates something</span><b name="data/ala2/wtmetad/plumed_gnn.datphi" onclick='showPath("data/ala2/wtmetad/plumed_gnn.dat","data/ala2/wtmetad/plumed_gnn.datphi","data/ala2/wtmetad/plumed_gnn.datphi","brown")'>phi</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=5,7,9,15
<span style="display:none;" id="data/ala2/wtmetad/plumed_gnn.datphi">The TORSION action with label <b>phi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/ala2/wtmetad/plumed_gnn.datpsi" onclick='showPath("data/ala2/wtmetad/plumed_gnn.dat","data/ala2/wtmetad/plumed_gnn.datpsi","data/ala2/wtmetad/plumed_gnn.datpsi","brown")'>psi</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=7,9,15,17

<span style="display:none;" id="data/ala2/wtmetad/plumed_gnn.datpsi">The TORSION action with label <b>psi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">psi.value</td><td>the TORSION involving these atoms</td></tr></table></span><span class="plumedtooltip" style="color:green">GRAPH<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> ...
 LABEL=<b name="data/ala2/wtmetad/plumed_gnn.datmodel" onclick='showPath("data/ala2/wtmetad/plumed_gnn.dat","data/ala2/wtmetad/plumed_gnn.datmodel","data/ala2/wtmetad/plumed_gnn.datmodel","brown")'>model</b>
 ATOMS=<b name="data/ala2/wtmetad/plumed_gnn.datHEAVY">HEAVY</b>
 RCUT=1.0
 MODEL=model.pt
... GRAPH
<br/><span class="plumedtooltip" style="color:green">METAD<span class="right">Used to performed metadynamics on one or more collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/METAD" style="color:green">More details</a><i></i></span></span> ...
 <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/ala2/wtmetad/plumed_gnn.datmetad" onclick='showPath("data/ala2/wtmetad/plumed_gnn.dat","data/ala2/wtmetad/plumed_gnn.datmetad","data/ala2/wtmetad/plumed_gnn.datmetad","brown")'>metad</b>
 <span class="plumedtooltip">ARG<span class="right">the labels of the scalars on which the bias will act<i></i></span></span>=model.node-0,model.node-1
 <span class="plumedtooltip">TEMP<span class="right">the system temperature - this is only needed if you are doing well-tempered metadynamics<i></i></span></span>=300
 <span class="plumedtooltip">SIGMA<span class="right">the widths of the Gaussian hills<i></i></span></span>=0.1,0.1
 <span class="plumedtooltip">HEIGHT<span class="right">the heights of the Gaussian hills<i></i></span></span>=1.25 
 <span class="plumedtooltip">FILE<span class="right"> a file in which the list of added hills is stored<i></i></span></span>=HILLS   <span style="color:blue" class="comment"># File where the information of the gaussians is printed</span>
 <span class="plumedtooltip">BIASFACTOR<span class="right">use well tempered metadynamics and use this bias factor<i></i></span></span>=5
 <span class="plumedtooltip">PACE<span class="right">the frequency for hill addition<i></i></span></span>=500
 <span class="plumedtooltip">GRID_MIN<span class="right">the lower bounds for the grid<i></i></span></span>=-10.0,-20.0 
 <span class="plumedtooltip">GRID_MAX<span class="right">the upper bounds for the grid<i></i></span></span>=30.0,15.0 
 <span class="plumedtooltip">GRID_BIN<span class="right">the number of bins for the grid<i></i></span></span>=500,500
 <span class="plumedtooltip">CALC_RCT<span class="right"> calculate the c(t) reweighting factor and use that to obtain the normalized bias [rbias=bias-rct]<i></i></span></span>
... METAD
<br/><span style="display:none;" id="data/ala2/wtmetad/plumed_gnn.datmetad">The METAD action with label <b>metad</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">metad.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">metad.rbias</td><td>the instantaneous value of the bias normalized using the c(t) reweighting factor [rbias=bias-rct]</td></tr><tr><td width="5%">metad.rct</td><td>the reweighting factor c(t)</td></tr></table></span><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=model.*,<b name="data/ala2/wtmetad/plumed_gnn.datphi">phi</b>,<b name="data/ala2/wtmetad/plumed_gnn.datpsi">psi</b>,<b name="data/ala2/wtmetad/plumed_gnn.datmetad">metad.*</b> <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=500 <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=COLVAR 
</pre>
{% endraw %}
