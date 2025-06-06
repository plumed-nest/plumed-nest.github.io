**Project ID:** [plumID:22.001]({{ '/' | absolute_url }}eggs/22/001/)  
**Source:** lammps/CaCO3/sym10/plumed.dat  
**Originally used with PLUMED version:** 2.8  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/lammps/CaCO3/sym10/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span style="color:blue" class="comment">#SETTINGS NREPLICAS=2</span>
<span class="plumedtooltip" style="color:blue"># vim:ft=plumed<span class="right">Enables syntax highlighting for PLUMED files in vim. See <a href="https://www.plumed.org/doc-master/user-doc/html/vim">here for more details. </a><i></i></span></span>
<span class="plumedtooltip" style="color:green">UNITS<span class="right">This command sets the internal units for the code. <a href="https://www.plumed.org/doc-master/user-doc/html/UNITS" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">LENGTH<span class="right">the units of lengths<i></i></span></span>=A <span class="plumedtooltip">ENERGY<span class="right">the units of energy<i></i></span></span>=eV

<span style="color:blue" class="comment"># CVs</span>
<span style="display:none;" id="data/lammps/CaCO3/sym10/plumed.dat">The UNITS action with label <b></b> calculates something</span><b name="data/lammps/CaCO3/sym10/plumed.datdist" onclick='showPath("data/lammps/CaCO3/sym10/plumed.dat","data/lammps/CaCO3/sym10/plumed.datdist","data/lammps/CaCO3/sym10/plumed.datdist","brown")'>dist</b>:  <span class="plumedtooltip" style="color:green">DISTANCE<span class="right">Calculate the distance/s between pairs of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/DISTANCE" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the pair of atom that we are calculating the distance between<i></i></span></span>=7345,7346

<span style="display:none;" id="data/lammps/CaCO3/sym10/plumed.datdist">The DISTANCE action with label <b>dist</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">dist.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><span class="plumedtooltip" style="color:green">COORDINATION<span class="right">Calculate coordination numbers. <a href="https://www.plumed.org/doc-master/user-doc/html/COORDINATION" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/lammps/CaCO3/sym10/plumed.datcoord" onclick='showPath("data/lammps/CaCO3/sym10/plumed.dat","data/lammps/CaCO3/sym10/plumed.datcoord","data/lammps/CaCO3/sym10/plumed.datcoord","brown")'>coord</b>
  <span class="plumedtooltip">GROUPA<span class="right">First list of atoms<i></i></span></span>=7345
  <span class="plumedtooltip">GROUPB<span class="right">Second list of atoms (if empty, N*(N-1)/2 pairs in GROUPA are counted)<i></i></span></span>=2-7343:3
  <span class="plumedtooltip">SWITCH<span class="right">This keyword is used if you want to employ an alternative to the continuous switching function defined above. Options for this keyword are explained in the documentation for <a href="https://www.plumed.org/doc-master/user-doc/html/LESS_THAN">LESS_THAN</a>.<i></i></span></span>={RATIONAL R_0=1.0 D_0=2.1 NN=4 MM=8}
  <span class="plumedtooltip">NLIST<span class="right"> Use a neighbor list to speed up the calculation<i></i></span></span>
  <span class="plumedtooltip">NL_CUTOFF<span class="right">The cutoff for the neighbor list<i></i></span></span>=10
  <span class="plumedtooltip">NL_STRIDE<span class="right">The frequency with which we are updating the atoms in the neighbor list<i></i></span></span>=10
... COORDINATION
<br/><span style="color:blue" class="comment"># Target distribution</span>
<span style="display:none;" id="data/lammps/CaCO3/sym10/plumed.datcoord">The COORDINATION action with label <b>coord</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">coord.value</td><td>the value of the coordination</td></tr></table></span><b name="data/lammps/CaCO3/sym10/plumed.dattd_wt" onclick='showPath("data/lammps/CaCO3/sym10/plumed.dat","data/lammps/CaCO3/sym10/plumed.dattd_wt","data/lammps/CaCO3/sym10/plumed.dattd_wt","brown")'>td_wt</b>: <span class="plumedtooltip" style="color:green">TD_WELLTEMPERED<span class="right">Well-tempered target distribution (dynamic). <a href="https://www.plumed.org/doc-master/user-doc/html/TD_WELLTEMPERED" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">BIASFACTOR<span class="right">The bias factor used for the well-tempered distribution<i></i></span></span>=5


<span style="color:blue" class="comment"># Basisset</span>
<span style="display:none;" id="data/lammps/CaCO3/sym10/plumed.dattd_wt">The TD_WELLTEMPERED action with label <b>td_wt</b> calculates something</span><span class="plumedtooltip" style="color:green">BF_WAVELETS<span class="right">Daubechies Wavelets basis functions. <a href="https://www.plumed.org/doc-master/user-doc/html/BF_WAVELETS" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/lammps/CaCO3/sym10/plumed.datbfdist" onclick='showPath("data/lammps/CaCO3/sym10/plumed.dat","data/lammps/CaCO3/sym10/plumed.datbfdist","data/lammps/CaCO3/sym10/plumed.datbfdist","brown")'>bfdist</b>
  <span class="plumedtooltip">ORDER<span class="right">The order of the basis function expansion<i></i></span></span>=10
  <span class="plumedtooltip">MINIMUM<span class="right">The minimum of the interval on which the basis functions are defined<i></i></span></span>=2
  <span class="plumedtooltip">MAXIMUM<span class="right">The maximum of the interval on which the basis functions are defined<i></i></span></span>=12
  <span class="plumedtooltip">FUNCTION_LENGTH<span class="right">The domain size of the individual basis functions<i></i></span></span>=3.65
  <span class="plumedtooltip">TYPE<span class="right">Specify the wavelet type<i></i></span></span>=SYMLETS
  <span class="plumedtooltip">TAILS_THRESHOLD<span class="right">The threshold for cutting off tail wavelets as a fraction of the maximum value<i></i></span></span>=0.01
... BF_WAVELETS
<br/><span style="display:none;" id="data/lammps/CaCO3/sym10/plumed.datbfdist">The BF_WAVELETS action with label <b>bfdist</b> calculates something</span><span class="plumedtooltip" style="color:green">BF_WAVELETS<span class="right">Daubechies Wavelets basis functions. <a href="https://www.plumed.org/doc-master/user-doc/html/BF_WAVELETS" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/lammps/CaCO3/sym10/plumed.datbfcoord" onclick='showPath("data/lammps/CaCO3/sym10/plumed.dat","data/lammps/CaCO3/sym10/plumed.datbfcoord","data/lammps/CaCO3/sym10/plumed.datbfcoord","brown")'>bfcoord</b>
  <span class="plumedtooltip">ORDER<span class="right">The order of the basis function expansion<i></i></span></span>=10
  <span class="plumedtooltip">MINIMUM<span class="right">The minimum of the interval on which the basis functions are defined<i></i></span></span>=5
  <span class="plumedtooltip">MAXIMUM<span class="right">The maximum of the interval on which the basis functions are defined<i></i></span></span>=9
  <span class="plumedtooltip">FUNCTION_LENGTH<span class="right">The domain size of the individual basis functions<i></i></span></span>=3.5
  <span class="plumedtooltip">TYPE<span class="right">Specify the wavelet type<i></i></span></span>=SYMLETS
  <span class="plumedtooltip">TAILS_THRESHOLD<span class="right">The threshold for cutting off tail wavelets as a fraction of the maximum value<i></i></span></span>=0.01
... BF_WAVELETS

<br/><span style="display:none;" id="data/lammps/CaCO3/sym10/plumed.datbfcoord">The BF_WAVELETS action with label <b>bfcoord</b> calculates something</span><span class="plumedtooltip" style="color:green">VES_LINEAR_EXPANSION<span class="right">Linear basis set expansion bias. <a href="https://www.plumed.org/doc-master/user-doc/html/VES_LINEAR_EXPANSION" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/lammps/CaCO3/sym10/plumed.datb1" onclick='showPath("data/lammps/CaCO3/sym10/plumed.dat","data/lammps/CaCO3/sym10/plumed.datb1","data/lammps/CaCO3/sym10/plumed.datb1","brown")'>b1</b>
  <span class="plumedtooltip">ARG<span class="right">the labels of the scalars on which the bias will act<i></i></span></span>=<b name="data/lammps/CaCO3/sym10/plumed.datdist">dist</b>,<b name="data/lammps/CaCO3/sym10/plumed.datcoord">coord</b>
  <span class="plumedtooltip">BASIS_FUNCTIONS<span class="right">the label of the one dimensional basis functions that should be used<i></i></span></span>=<b name="data/lammps/CaCO3/sym10/plumed.datbfdist">bfdist</b>,<b name="data/lammps/CaCO3/sym10/plumed.datbfcoord">bfcoord</b>
  <span class="plumedtooltip">TEMP<span class="right">the system temperature - this is needed if the MD code does not pass the temperature to PLUMED<i></i></span></span>=300.0
  <span class="plumedtooltip">GRID_BINS<span class="right">the number of bins used for the grid<i></i></span></span>=300,300
  <span class="plumedtooltip">OPTIMIZATION_THRESHOLD<span class="right">Threshold value to turn off optimization of localized basis functions<i></i></span></span>=0.000001
  <span class="plumedtooltip">TARGET_DISTRIBUTION<span class="right">the label of the target distribution to be used<i></i></span></span>=<b name="data/lammps/CaCO3/sym10/plumed.dattd_wt">td_wt</b>
... VES_LINEAR_EXPANSION
<br/><span style="display:none;" id="data/lammps/CaCO3/sym10/plumed.datb1">The VES_LINEAR_EXPANSION action with label <b>b1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">b1.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">b1.force2</td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span><span class="plumedtooltip" style="color:green">OPT_AVERAGED_SGD<span class="right">Averaged stochastic gradient decent with fixed step size. <a href="https://www.plumed.org/doc-master/user-doc/html/OPT_AVERAGED_SGD" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/lammps/CaCO3/sym10/plumed.dato1" onclick='showPath("data/lammps/CaCO3/sym10/plumed.dat","data/lammps/CaCO3/sym10/plumed.dato1","data/lammps/CaCO3/sym10/plumed.dato1","brown")'>o1</b>
  <span class="plumedtooltip">BIAS<span class="right">the label of the VES bias to be optimized<i></i></span></span>=<b name="data/lammps/CaCO3/sym10/plumed.datb1">b1</b>
  <span class="plumedtooltip">STRIDE<span class="right">the frequency of updating the coefficients given in the number of MD steps<i></i></span></span>=10
  <span class="plumedtooltip">STEPSIZE<span class="right">the step size used for the optimization<i></i></span></span>=0.001
  <span class="plumedtooltip">FES_OUTPUT<span class="right">how often the FES(s) should be written out to file<i></i></span></span>=100
  <span class="plumedtooltip">BIAS_OUTPUT<span class="right">how often the bias(es) should be written out to file<i></i></span></span>=100
  <span class="plumedtooltip">COEFFS_OUTPUT<span class="right"> how often the coefficients should be written to file<i></i></span></span>=10
  <span class="plumedtooltip">TARGETDIST_STRIDE<span class="right">stride for updating a target distribution that is iteratively updated during the optimization<i></i></span></span>=100
  <span class="plumedtooltip">TARGETDIST_OUTPUT<span class="right">how often the dynamic target distribution(s) should be written out to file<i></i></span></span>=100
  <span class="plumedtooltip">MULTIPLE_WALKERS<span class="right"> if optimization is to be performed using multiple walkers connected via MPI<i></i></span></span>
... OPT_AVERAGED_SGD
<br/><span style="display:none;" id="data/lammps/CaCO3/sym10/plumed.dato1">The OPT_AVERAGED_SGD action with label <b>o1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">o1.value</td><td>a scalar</td></tr></table></span><span class="plumedtooltip" style="color:green">UPPER_WALLS<span class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/UPPER_WALLS" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">ARG<span class="right">the arguments on which the bias is acting<i></i></span></span>=<b name="data/lammps/CaCO3/sym10/plumed.datdist">dist</b>
  <span class="plumedtooltip">AT<span class="right">the positions of the wall<i></i></span></span>=12
  <span class="plumedtooltip">KAPPA<span class="right">the force constant for the wall<i></i></span></span>=12.0
  <span class="plumedtooltip">EXP<span class="right"> the powers for the walls<i></i></span></span>=2
  <span class="plumedtooltip">EPS<span class="right"> the values for s_i in the expression for a wall<i></i></span></span>=1
  <span class="plumedtooltip">OFFSET<span class="right"> the offset for the start of the wall<i></i></span></span>=0.
  <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/lammps/CaCO3/sym10/plumed.datwall" onclick='showPath("data/lammps/CaCO3/sym10/plumed.dat","data/lammps/CaCO3/sym10/plumed.datwall","data/lammps/CaCO3/sym10/plumed.datwall","brown")'>wall</b>
... UPPER_WALLS
<br/><span style="display:none;" id="data/lammps/CaCO3/sym10/plumed.datwall">The UPPER_WALLS action with label <b>wall</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">wall.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">wall.force2</td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span><span class="plumedtooltip" style="color:green">FLUSH<span class="right">This command instructs plumed to flush all the open files with a user specified frequency. <a href="https://www.plumed.org/doc-master/user-doc/html/FLUSH" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">STRIDE<span class="right">the frequency with which all the open files should be flushed<i></i></span></span>=100
<span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=* <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=100 <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=COLVAR
</pre>
{% endraw %}
