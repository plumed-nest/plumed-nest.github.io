**Project ID:** [plumID:20.024]({{ '/' | absolute_url }}eggs/20/024/)  
**Source:** Alanine-dipeptide/static_bias/plumed.dat  
**Originally used with PLUMED version:** 2.7  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/Alanine-dipeptide/static_bias/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></div>
<div class="headerBadge"><img src="https://img.shields.io/badge/with-LOAD-yellow.svg" alt="tested on master" /></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:blue"># vim:ft=plumed<span class="right">Enables syntax highlighting for PLUMED files in vim. See <a href="https://www.plumed.org/doc-master/user-doc/html/vim">here for more details. </a><i></i></span></span>
<span class="plumedtooltip" style="color:green">LOAD<span class="right">Loads a library, possibly defining new actions. <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FILE<span class="right">file to be loaded<i></i></span></span>=../../GAMBES.cpp

<span style="color:blue" class="comment"># Descriptors</span>
<span style="display:none;" id="data/Alanine-dipeptide/static_bias/plumed.dat">The LOAD action with label <b></b> calculates something</span><b name="data/Alanine-dipeptide/static_bias/plumed.datphi" onclick='showPath("data/Alanine-dipeptide/static_bias/plumed.dat","data/Alanine-dipeptide/static_bias/plumed.datphi","data/Alanine-dipeptide/static_bias/plumed.datphi","brown")'>phi</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=5,7,9,15
<span style="display:none;" id="data/Alanine-dipeptide/static_bias/plumed.datphi">The TORSION action with label <b>phi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/Alanine-dipeptide/static_bias/plumed.datpsi" onclick='showPath("data/Alanine-dipeptide/static_bias/plumed.dat","data/Alanine-dipeptide/static_bias/plumed.datpsi","data/Alanine-dipeptide/static_bias/plumed.datpsi","brown")'>psi</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=7,9,15,17

<span style="color:blue" class="comment"># Bias</span>
<span style="display:none;" id="data/Alanine-dipeptide/static_bias/plumed.datpsi">The TORSION action with label <b>psi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">psi.value</td><td>the TORSION involving these atoms</td></tr></table></span><span class="plumedtooltip" style="color:green">GAMBES<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> ...
  ARG=<b name="data/Alanine-dipeptide/static_bias/plumed.datphi">phi</b>,<b name="data/Alanine-dipeptide/static_bias/plumed.datpsi">psi</b>
  NSTATES=2
  FILENAME=state
  PACE=500
  LABEL=<b name="data/Alanine-dipeptide/static_bias/plumed.datext" onclick='showPath("data/Alanine-dipeptide/static_bias/plumed.dat","data/Alanine-dipeptide/static_bias/plumed.datext","data/Alanine-dipeptide/static_bias/plumed.datext","brown")'>ext</b>
  BIAS_CUTOFF
  CUTOFF=30
  LAMBDA=1
  STATIC_BIAS
  STATIC_FACTORS=1,0.035
... GAMBES


<br/><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=* <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=10 <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=COLVAR <span class="plumedtooltip">FMT<span class="right"> the format that should be used to output real numbers<i></i></span></span>=%.9f
</pre>
{% endraw %}
