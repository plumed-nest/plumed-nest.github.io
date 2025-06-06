**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
**Source:** atlas_inputs/di_pept/plumed_biased.dat  
**Originally used with PLUMED version:** 2.7-mod  
**Stable:** [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) - [stderr](plumed_biased.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed_biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed_master.stderr.txt.zip) - [stderr](plumed_biased.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/atlas_inputs/di_pept/plumed_biased.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed_biased.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed_biased.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span style="color:blue" class="comment">#</span>
<span class="plumedtooltip" style="color:green">UNITS<span class="right">This command sets the internal units for the code. <a href="https://www.plumed.org/doc-master/user-doc/html/UNITS" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ENERGY<span class="right">the units of energy<i></i></span></span>=kj/mol
<span style="display:none;" id="data/atlas_inputs/di_pept/plumed_biased.dat">The UNITS action with label <b></b> calculates something</span><b name="data/atlas_inputs/di_pept/plumed_biased.datt1" onclick='showPath("data/atlas_inputs/di_pept/plumed_biased.dat","data/atlas_inputs/di_pept/plumed_biased.datt1","data/atlas_inputs/di_pept/plumed_biased.datt1","brown")'>t1</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=5,7,9,15
<span style="display:none;" id="data/atlas_inputs/di_pept/plumed_biased.datt1">The TORSION action with label <b>t1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">t1.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/atlas_inputs/di_pept/plumed_biased.datt2" onclick='showPath("data/atlas_inputs/di_pept/plumed_biased.dat","data/atlas_inputs/di_pept/plumed_biased.datt2","data/atlas_inputs/di_pept/plumed_biased.datt2","brown")'>t2</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=7,9,15,17


<span style="display:none;" id="data/atlas_inputs/di_pept/plumed_biased.datt2">The TORSION action with label <b>t2</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">t2.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/atlas_inputs/di_pept/plumed_biased.datat" onclick='showPath("data/atlas_inputs/di_pept/plumed_biased.dat","data/atlas_inputs/di_pept/plumed_biased.datat","data/atlas_inputs/di_pept/plumed_biased.datat","brown")'>at</b>: <span class="plumedtooltip" style="color:green">ATLAS<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> ...
REFERENCE=cluster_plumed.dat PACE=500
ARG=<b name="data/atlas_inputs/di_pept/plumed_biased.datt1">t1</b>,<b name="data/atlas_inputs/di_pept/plumed_biased.datt2">t2</b>
SIGMA=0.10 BIASFACTOR=10 HEIGHT=2.0
GRID_MAX=5.0 GRID_BIN=500 TEMP=300 TRUNCATE_GRIDS
REGULARISE=1E-6
STATIC_WALL=0.0
ADAPTIVE_WALL=1.0
...

<br/><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=<b name="data/atlas_inputs/di_pept/plumed_biased.datt1">t1</b>,<b name="data/atlas_inputs/di_pept/plumed_biased.datt2">t2</b> <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=colvar <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=500
<span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=at,at_wtfact <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=at.gbias <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=500
<span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=at_adaptive_wall <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=wall <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=500
</pre>
{% endraw %}
