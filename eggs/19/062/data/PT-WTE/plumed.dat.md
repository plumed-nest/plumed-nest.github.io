**Project ID:** [plumID:19.062]({{ '/' | absolute_url }}eggs/19/062/)  
**Source:** PT-WTE/plumed.dat  
**Originally used with PLUMED version:** 2.3  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/PT-WTE/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span style="color:blue" class="comment">#RESTART</span>
<b name="data/PT-WTE/plumed.daten" onclick='showPath("data/PT-WTE/plumed.dat","data/PT-WTE/plumed.daten","data/PT-WTE/plumed.daten","brown")'>en</b>: <span class="plumedtooltip" style="color:green">ENERGY<span class="right">Calculate the total potential energy of the simulation box. <a href="https://www.plumed.org/doc-master/user-doc/html/ENERGY" style="color:green">More details</a><i></i></span></span>
<span style="display:none;" id="data/PT-WTE/plumed.daten">The ENERGY action with label <b>en</b> calculates something</span><span class="plumedtooltip" style="color:green">WHOLEMOLECULES<span class="right">This action is used to rebuild molecules that can become split by the periodic boundary conditions. <a href="https://www.plumed.org/doc-master/user-doc/html/WHOLEMOLECULES" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ENTITY0<span class="right">the atoms that make up a molecule that you wish to align<i></i></span></span>=1-558

<span style="display:none;" id="data/PT-WTE/plumed.dat">The WHOLEMOLECULES action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">GYRATION<span class="right">Calculate the radius of gyration, or other properties related to it. <a href="https://www.plumed.org/doc-master/user-doc/html/GYRATION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">TYPE<span class="right"> The type of calculation relative to the Gyration Tensor you want to perform<i></i></span></span>=RADIUS <span class="plumedtooltip">ATOMS<span class="right">the group of atoms that you are calculating the Gyration Tensor for<i></i></span></span>=5,20,42,57,79,94,116,131,153,168,190,205,227,242,264,279,301,316,338,353,375,390,412,427,449,464,486,501,523,538 <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/PT-WTE/plumed.datrg" onclick='showPath("data/PT-WTE/plumed.dat","data/PT-WTE/plumed.datrg","data/PT-WTE/plumed.datrg","brown")'>rg</b>

<br/><span style="display:none;" id="data/PT-WTE/plumed.datrg">The GYRATION action with label <b>rg</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">rg.value</td><td>the radius that was computed from the weights</td></tr></table></span><span class="plumedtooltip" style="color:green">METAD<span class="right">Used to performed metadynamics on one or more collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/METAD" style="color:green">More details</a><i></i></span></span> ...
<span class="plumedtooltip">ARG<span class="right">the labels of the scalars on which the bias will act<i></i></span></span>=<b name="data/PT-WTE/plumed.daten">en</b>
<span class="plumedtooltip">PACE<span class="right">the frequency for hill addition<i></i></span></span>=250 <span class="plumedtooltip">BIASFACTOR<span class="right">use well tempered metadynamics and use this bias factor<i></i></span></span>=30.0 <span class="plumedtooltip">HEIGHT<span class="right">the heights of the Gaussian hills<i></i></span></span>=4.18 
<span class="plumedtooltip">SIGMA<span class="right">the widths of the Gaussian hills<i></i></span></span>=250
<span class="plumedtooltip">GRID_MIN<span class="right">the lower bounds for the grid<i></i></span></span>=-300000.000000
<span class="plumedtooltip">GRID_MAX<span class="right">the upper bounds for the grid<i></i></span></span>=-200000.000000
<span class="plumedtooltip">FILE<span class="right"> a file in which the list of added hills is stored<i></i></span></span>=HILLS
... METAD
<br/><span style="color:blue" class="comment">#make STRIDE = to your exchange attempt frequency!!!</span>
<span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=COLVAR <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=<b name="data/PT-WTE/plumed.daten">en</b>,<b name="data/PT-WTE/plumed.datrg">rg</b> <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=250
</pre>
{% endraw %}
