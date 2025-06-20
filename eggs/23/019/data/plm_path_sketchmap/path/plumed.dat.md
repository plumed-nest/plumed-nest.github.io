**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
**Source:** plm_path_sketchmap/path/plumed.dat  
**Originally used with PLUMED version:** 2.7.2  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/plm_path_sketchmap/path/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:green">WHOLEMOLECULES<span class="right">This action is used to rebuild molecules that can become split by the periodic boundary conditions. <a href="https://www.plumed.org/doc-master/user-doc/html/WHOLEMOLECULES" style="color:green">More details</a><i></i></span></span> ...
	<span class="plumedtooltip">ENTITY0<span class="right">the atoms that make up a molecule that you wish to align<i></i></span></span>=1-6304 <span style="color:blue" class="comment"># plm5</span>
	<span class="plumedtooltip">ENTITY1<span class="right">the atoms that make up a molecule that you wish to align<i></i></span></span>=6305-6353 <span style="color:blue" class="comment"># lig</span>
... WHOLEMOLECULES
<br/><span style="display:none;" id="data/plm_path_sketchmap/path/plumed.dat">The WHOLEMOLECULES action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">PATHMSD<span class="right">This Colvar calculates path collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/PATHMSD" style="color:green">More details</a><i></i></span></span> ...
	<span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/plm_path_sketchmap/path/plumed.datp1" onclick='showPath("data/plm_path_sketchmap/path/plumed.dat","data/plm_path_sketchmap/path/plumed.datp1","data/plm_path_sketchmap/path/plumed.datp1","brown")'>p1</b>
	<span class="plumedtooltip">REFERENCE<span class="right">the pdb is needed to provide the various milestones<i></i></span></span>=path_15f.pdb
	<span class="plumedtooltip">LAMBDA<span class="right">the lambda parameter is needed for smoothing, is in the units of plumed<i></i></span></span>=961 <span style="color:blue" class="comment"># lambda=2.3/(average_RMSD_between_frames)**2    2.3/0.048907^2</span>
	<span class="plumedtooltip">NEIGH_SIZE<span class="right">size of the neighbor list<i></i></span></span>=5
... PATHMSD
<br/><span style="display:none;" id="data/plm_path_sketchmap/path/plumed.datp1">The PATHMSD action with label <b>p1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p1.sss</td><td>the position on the path</td></tr><tr><td width="5%">p1.zzz</td><td>the distance from the path</td></tr></table></span><span class="plumedtooltip" style="color:green">METAD<span class="right">Used to performed metadynamics on one or more collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/METAD" style="color:green">More details</a><i></i></span></span> ...
	<span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/plm_path_sketchmap/path/plumed.datmetad" onclick='showPath("data/plm_path_sketchmap/path/plumed.dat","data/plm_path_sketchmap/path/plumed.datmetad","data/plm_path_sketchmap/path/plumed.datmetad","brown")'>metad</b>
	<span class="plumedtooltip">ARG<span class="right">the labels of the scalars on which the bias will act<i></i></span></span>=<b name="data/plm_path_sketchmap/path/plumed.datp1">p1.sss</b>,<b name="data/plm_path_sketchmap/path/plumed.datp1">p1.zzz</b>
	<span class="plumedtooltip">SIGMA<span class="right">the widths of the Gaussian hills<i></i></span></span>=0.1,0.001
	<span class="plumedtooltip">HEIGHT<span class="right">the heights of the Gaussian hills<i></i></span></span>=3.0
	<span class="plumedtooltip">PACE<span class="right">the frequency for hill addition<i></i></span></span>=500
	<span class="plumedtooltip">TEMP<span class="right">the system temperature - this is only needed if you are doing well-tempered metadynamics<i></i></span></span>=298
	<span class="plumedtooltip">BIASFACTOR<span class="right">use well tempered metadynamics and use this bias factor<i></i></span></span>=10
	<span class="plumedtooltip">GRID_MIN<span class="right">the lower bounds for the grid<i></i></span></span>=-1,-0.1
	<span class="plumedtooltip">GRID_MAX<span class="right">the upper bounds for the grid<i></i></span></span>=16,0.2
	<span class="plumedtooltip">GRID_BIN<span class="right">the number of bins for the grid<i></i></span></span>=400,800
	<span class="plumedtooltip">CALC_RCT<span class="right"> calculate the c(t) reweighting factor and use that to obtain the normalized bias [rbias=bias-rct]<i></i></span></span>
	<span class="plumedtooltip">FMT<span class="right">specify format for HILLS files (useful for decrease the number of digits in regtests)<i></i></span></span>=%8.4f
... METAD
<br/><span style="display:none;" id="data/plm_path_sketchmap/path/plumed.datmetad">The METAD action with label <b>metad</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">metad.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">metad.rbias</td><td>the instantaneous value of the bias normalized using the c(t) reweighting factor [rbias=bias-rct]</td></tr><tr><td width="5%">metad.rct</td><td>the reweighting factor c(t)</td></tr></table></span><span class="plumedtooltip" style="color:green">UPPER_WALLS<span class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/UPPER_WALLS" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the arguments on which the bias is acting<i></i></span></span>=<b name="data/plm_path_sketchmap/path/plumed.datp1">p1.zzz</b> <span class="plumedtooltip">AT<span class="right">the positions of the wall<i></i></span></span>=0.05 <span class="plumedtooltip">KAPPA<span class="right">the force constant for the wall<i></i></span></span>=50000 <span class="plumedtooltip">EXP<span class="right"> the powers for the walls<i></i></span></span>=2 <span class="plumedtooltip">OFFSET<span class="right"> the offset for the start of the wall<i></i></span></span>=0 <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/plm_path_sketchmap/path/plumed.datp1-zzz_uwall" onclick='showPath("data/plm_path_sketchmap/path/plumed.dat","data/plm_path_sketchmap/path/plumed.datp1-zzz_uwall","data/plm_path_sketchmap/path/plumed.datp1-zzz_uwall","brown")'>p1-zzz_uwall</b>
<br/><span style="display:none;" id="data/plm_path_sketchmap/path/plumed.datp1-zzz_uwall">The UPPER_WALLS action with label <b>p1-zzz_uwall</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p1-zzz_uwall.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">p1-zzz_uwall.force2</td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> ...
	<span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=25
	<span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=*
	<span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=COLVAR
	<span class="plumedtooltip">FMT<span class="right"> the format that should be used to output real numbers<i></i></span></span>=%8.4f
... PRINT
</pre>
{% endraw %}
