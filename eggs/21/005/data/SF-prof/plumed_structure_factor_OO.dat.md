**Project ID:** [plumID:21.005]({{ '/' | absolute_url }}eggs/21/005/)  
**Source:** SF-prof/plumed_structure_factor_OO.dat  
**Originally used with PLUMED version:** 2.7-mod  
**Stable:** [zipped raw stdout](plumed_structure_factor_OO.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_structure_factor_OO.dat.plumed.stderr.txt.zip) - [stderr](plumed_structure_factor_OO.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed_structure_factor_OO.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_structure_factor_OO.dat.plumed_master.stderr.txt.zip) - [stderr](plumed_structure_factor_OO.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/SF-prof/plumed_structure_factor_OO.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed_structure_factor_OO.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed_structure_factor_OO.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></div>
<div class="headerBadge"><img src="https://img.shields.io/badge/with-LOAD-yellow.svg" alt="tested on master" /></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:blue"># vim:ft=plumed<span class="right">Enables syntax highlighting for PLUMED files in vim. See <a href="https://www.plumed.org/doc-master/user-doc/html/vim">here for more details. </a><i></i></span></span>
<span class="plumedtooltip" style="color:green">LOAD<span class="right">Loads a library, possibly defining new actions. <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FILE<span class="right">file to be loaded<i></i></span></span>=../codes/StructureFactor_sphericallyAveraged.cpp

<span style="display:none;" id="data/SF-prof/plumed_structure_factor_OO.dat">The LOAD action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">GROUP<span class="right">Define a group of atoms so that a particular list of atoms can be referenced with a single label in definitions of CVs or virtual atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/GROUP" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the numerical indexes for the set of atoms in the group<i></i></span></span>=2-324:3,3-324:3 <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/SF-prof/plumed_structure_factor_OO.datO" onclick='showPath("data/SF-prof/plumed_structure_factor_OO.dat","data/SF-prof/plumed_structure_factor_OO.datO","data/SF-prof/plumed_structure_factor_OO.datO","brown")'>O</b>
<br/><span style="display:none;" id="data/SF-prof/plumed_structure_factor_OO.datO">The GROUP action with label <b>O</b> calculates something</span><b name="data/SF-prof/plumed_structure_factor_OO.datsf" onclick='showPath("data/SF-prof/plumed_structure_factor_OO.dat","data/SF-prof/plumed_structure_factor_OO.datsf","data/SF-prof/plumed_structure_factor_OO.datsf","brown")'>sf</b>: <span class="plumedtooltip" style="color:green">STRUCTURE_FACTOR_SPHERICALLY_AVERAGED<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> N2_MAX=250 ATOMS=<b name="data/SF-prof/plumed_structure_factor_OO.datO">O</b> 

<span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FMT<span class="right"> the format that should be used to output real numbers<i></i></span></span>=%g <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=1 <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=COLVAR-sfOO <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=sf.*
</pre>
{% endraw %}
