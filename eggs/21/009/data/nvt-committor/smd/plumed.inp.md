**Project ID:** [plumID:21.009]({{ '/' | absolute_url }}eggs/21/009/)  
**Source:** nvt-committor/smd/plumed.inp  
**Originally used with PLUMED version:** 2.6  
**Stable:** [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) - [stderr](plumed.inp.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) - [stderr](plumed.inp.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/nvt-committor/smd/plumed.inp"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed.inp.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed.inp.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:green">UNITS<span class="right">This command sets the internal units for the code. <a href="https://www.plumed.org/doc-master/user-doc/html/UNITS" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">LENGTH<span class="right">the units of lengths<i></i></span></span>=A

<span style="display:none;" id="data/nvt-committor/smd/plumed.inp">The UNITS action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">COORDINATIONNUMBER<span class="right">Calculate the coordination numbers of atoms so that you can then calculate functions of the distribution of <a href="https://www.plumed.org/doc-master/user-doc/html/COORDINATIONNUMBER" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/nvt-committor/smd/plumed.inpcoord" onclick='showPath("data/nvt-committor/smd/plumed.inp","data/nvt-committor/smd/plumed.inpcoord","data/nvt-committor/smd/plumed.inpcoord","brown")'>coord</b>
  <span class="plumedtooltip">SPECIES<span class="right">the list of atoms for which the symmetry function is being calculated and the atoms that can be in the environments<i></i></span></span>=1-512
  <span class="plumedtooltip">SWITCH<span class="right">the switching function that it used in the construction of the contact matrix. Options for this keyword are explained in the documentation for <a href="https://www.plumed.org/doc-master/user-doc/html/LESS_THAN">LESS_THAN</a>.<i></i></span></span>={RATIONAL R_0=5.0 D_MAX=10.0}
  <span class="plumedtooltip">MORE_THAN<span class="right">calculate the number of variables that are more than a certain target value. Options for this keyword are explained in the documentation for <a href="https://www.plumed.org/doc-master/user-doc/html/MORE_THAN">MORE_THAN</a>.<i></i></span></span>={RATIONAL R_0=5.0 D_MAX=5.5}
  <span class="plumedtooltip">LOWMEM<span class="right">Including this keyword in the input to this action makes no difference to the calculation performed it was used in older versions of PLUMED and is provided here for back compatibility only<i></i></span></span>
... COORDINATIONNUMBER
<br/><span style="display:none;" id="data/nvt-committor/smd/plumed.inpcoord">The COORDINATIONNUMBER action with label <b>coord</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">coord.morethan</td><td>the number of colvars that have a value more than a threshold</td></tr><tr><td width="5%">coord.value</td><td>the coordination numbers of the specified atoms</td></tr></table></span><span class="plumedtooltip" style="color:green">MOVINGRESTRAINT<span class="right">Add a time-dependent, harmonic restraint on one or more variables. <a href="https://www.plumed.org/doc-master/user-doc/html/MOVINGRESTRAINT" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">ARG<span class="right">the labels of the scalars on which the bias will act<i></i></span></span>=<b name="data/nvt-committor/smd/plumed.inpcoord">coord.morethan</b>
  <span class="plumedtooltip">STEP0<span class="right">This keyword appears multiple times as STEPx with x=0,1,2,<i></i></span></span>=0       <span class="plumedtooltip">AT0<span class="right">ATx is equal to the position of the restraint at time STEPx<i></i></span></span>=0.0  <span class="plumedtooltip">KAPPA0<span class="right">KAPPAx is equal to the value of the force constants at time STEPx<i></i></span></span>=10.0
  <span class="plumedtooltip">STEP1<span class="right">This keyword appears multiple times as STEPx with x=0,1,2,<i></i></span></span>=2000000 <span class="plumedtooltip">AT1<span class="right">ATx is equal to the position of the restraint at time STEPx<i></i></span></span>=24.0 <span class="plumedtooltip">KAPPA1<span class="right">KAPPAx is equal to the value of the force constants at time STEPx<i></i></span></span>=10.0
... MOVINGRESTRAINT
<br/><span class="plumedtooltip" style="color:green">FLUSH<span class="right">This command instructs plumed to flush all the open files with a user specified frequency. <a href="https://www.plumed.org/doc-master/user-doc/html/FLUSH" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">STRIDE<span class="right">the frequency with which all the open files should be flushed<i></i></span></span>=200000
<span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=<b name="data/nvt-committor/smd/plumed.inpcoord">coord.morethan</b> <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=2000 <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=colvar
</pre>
{% endraw %}
