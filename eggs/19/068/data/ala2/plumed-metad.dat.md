**Project ID:** [plumID:19.068]({{ '/' | absolute_url }}eggs/19/068/)  
**Source:** ala2/plumed-metad.dat  
**Originally used with PLUMED version:** 2.7  
**Stable:** [zipped raw stdout](plumed-metad.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-metad.dat.plumed.stderr.txt.zip) - [stderr](plumed-metad.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed-metad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-metad.dat.plumed_master.stderr.txt.zip) - [stderr](plumed-metad.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/ala2/plumed-metad.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed-metad.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed-metad.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:blue"># vim:ft=plumed<span class="right">Enables syntax highlighting for PLUMED files in vim. See <a href="https://www.plumed.org/doc-master/user-doc/html/vim">here for more details. </a><i></i></span></span>
<br/><b name="data/ala2/plumed-metad.datphi" onclick='showPath("data/ala2/plumed-metad.dat","data/ala2/plumed-metad.datphi","data/ala2/plumed-metad.datphi","brown")'>phi</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=5,7,9,15
<span style="display:none;" id="data/ala2/plumed-metad.datphi">The TORSION action with label <b>phi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/ala2/plumed-metad.datpsi" onclick='showPath("data/ala2/plumed-metad.dat","data/ala2/plumed-metad.datpsi","data/ala2/plumed-metad.datpsi","brown")'>psi</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=7,9,15,17

<span style="display:none;" id="data/ala2/plumed-metad.datpsi">The TORSION action with label <b>psi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">psi.value</td><td>the TORSION involving these atoms</td></tr></table></span><span class="plumedtooltip" style="color:green">METAD<span class="right">Used to performed metadynamics on one or more collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/METAD" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/ala2/plumed-metad.datmetad" onclick='showPath("data/ala2/plumed-metad.dat","data/ala2/plumed-metad.datmetad","data/ala2/plumed-metad.datmetad","brown")'>metad</b>
  <span class="plumedtooltip">ARG<span class="right">the labels of the scalars on which the bias will act<i></i></span></span>=<b name="data/ala2/plumed-metad.datphi">phi</b>,<b name="data/ala2/plumed-metad.datpsi">psi</b>
  <span class="plumedtooltip">FILE<span class="right"> a file in which the list of added hills is stored<i></i></span></span>=Hills.data
  <span class="plumedtooltip">TEMP<span class="right">the system temperature - this is only needed if you are doing well-tempered metadynamics<i></i></span></span>=300.0
  <span class="plumedtooltip">PACE<span class="right">the frequency for hill addition<i></i></span></span>=500
  <span class="plumedtooltip">HEIGHT<span class="right">the heights of the Gaussian hills<i></i></span></span>=1.2
  <span class="plumedtooltip">SIGMA<span class="right">the widths of the Gaussian hills<i></i></span></span>=0.35,0.35
  <span class="plumedtooltip">BIASFACTOR<span class="right">use well tempered metadynamics and use this bias factor<i></i></span></span>=10.0
  <span class="plumedtooltip">GRID_MIN<span class="right">the lower bounds for the grid<i></i></span></span>=-pi,-pi
  <span class="plumedtooltip">GRID_MAX<span class="right">the upper bounds for the grid<i></i></span></span>=pi,pi
  <span class="plumedtooltip">GRID_BIN<span class="right">the number of bins for the grid<i></i></span></span>=100,100
  <span class="plumedtooltip">CALC_MAX_BIAS<span class="right"> Set to TRUE if you want to compute the maximum of the metadynamics V(s, t)<i></i></span></span>
  <span class="plumedtooltip">CALC_RCT<span class="right"> calculate the c(t) reweighting factor and use that to obtain the normalized bias [rbias=bias-rct]<i></i></span></span>
... METAD
<br/><span style="display:none;" id="data/ala2/plumed-metad.datmetad">The METAD action with label <b>metad</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">metad.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">metad.rbias</td><td>the instantaneous value of the bias normalized using the c(t) reweighting factor [rbias=bias-rct]</td></tr><tr><td width="5%">metad.rct</td><td>the reweighting factor c(t)</td></tr><tr><td width="5%">metad.maxbias</td><td>the maximum of the metadynamics V(s, t)</td></tr></table></span><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FMT<span class="right"> the format that should be used to output real numbers<i></i></span></span>=%g <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=500 <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=Colvar.data <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=<b name="data/ala2/plumed-metad.datphi">phi</b>,<b name="data/ala2/plumed-metad.datpsi">psi</b>,<b name="data/ala2/plumed-metad.datmetad">metad.bias</b>,<b name="data/ala2/plumed-metad.datmetad">metad.rct</b>,<b name="data/ala2/plumed-metad.datmetad">metad.maxbias</b>

<span style="display:none;" id="data/ala2/plumed-metad.dat">The PRINT action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">ENDPLUMED<span class="right">Terminate plumed input. <a href="https://www.plumed.org/doc-master/user-doc/html/ENDPLUMED" style="color:green">More details</a><i></i></span></span><span style="color:blue" class="comment">
</span></pre>
{% endraw %}
