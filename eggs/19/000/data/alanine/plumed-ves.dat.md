**Project ID:** [plumID:19.000]({{ '/' | absolute_url }}eggs/19/000/)  
**Source:** alanine/plumed-ves.dat  
**Originally used with PLUMED version:** 2.6-dev  
**Stable:** [zipped raw stdout](plumed-ves.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-ves.dat.plumed.stderr.txt.zip) - [stderr](plumed-ves.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed-ves.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-ves.dat.plumed_master.stderr.txt.zip) - [stderr](plumed-ves.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/alanine/plumed-ves.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed-ves.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed-ves.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:blue"># vim:ft=plumed<span class="right">Enables syntax highlighting for PLUMED files in vim. See <a href="https://www.plumed.org/doc-master/user-doc/html/vim">here for more details. </a><i></i></span></span>
<br/><b name="data/alanine/plumed-ves.datphi" onclick='showPath("data/alanine/plumed-ves.dat","data/alanine/plumed-ves.datphi","data/alanine/plumed-ves.datphi","brown")'>phi</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=5,7,9,15
<span style="display:none;" id="data/alanine/plumed-ves.datphi">The TORSION action with label <b>phi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/alanine/plumed-ves.datpsi" onclick='showPath("data/alanine/plumed-ves.dat","data/alanine/plumed-ves.datpsi","data/alanine/plumed-ves.datpsi","brown")'>psi</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=7,9,15,17

<span style="display:none;" id="data/alanine/plumed-ves.datpsi">The TORSION action with label <b>psi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">psi.value</td><td>the TORSION involving these atoms</td></tr></table></span><span class="plumedtooltip" style="color:green">VES_DELTA_F<span class="right">Implementation of VES Delta F method <a href="https://www.plumed.org/doc-master/user-doc/html/VES_DELTA_F" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/alanine/plumed-ves.datves" onclick='showPath("data/alanine/plumed-ves.dat","data/alanine/plumed-ves.datves","data/alanine/plumed-ves.datves","brown")'>ves</b>
  <span class="plumedtooltip">ARG<span class="right">the labels of the scalars on which the bias will act<i></i></span></span>=<b name="data/alanine/plumed-ves.datpsi">psi</b>
  <span class="plumedtooltip">TEMP<span class="right">temperature is compulsory, but it can be sometimes fetched from the MD engine<i></i></span></span>=300.0
  <span class="plumedtooltip">FILE_F0<span class="right">names of files containing local free energies and derivatives<i></i></span></span>=fesB.data
  <span class="plumedtooltip">FILE_F1<span class="right">names of files containing local free energies and derivatives<i></i></span></span>=fesA.data
  <span class="plumedtooltip">BIASFACTOR<span class="right"> the gamma bias factor used for well-tempered target p(s)<i></i></span></span>=10.0
  <span class="plumedtooltip">AV_STRIDE<span class="right"> number of simulation steps between alpha updates<i></i></span></span>=500
  <span class="plumedtooltip">M_STEP<span class="right"> the mu step used for the Omega functional minimization<i></i></span></span>=0.05
  <span class="plumedtooltip">PRINT_STRIDE<span class="right"> stride for printing to ALPHA_FILE<i></i></span></span>=100
  <span class="plumedtooltip">ALPHA_FILE<span class="right"> file name for output minimization parameters<i></i></span></span>=Alpha.data
... VES_DELTA_F
<br/><span style="display:none;" id="data/alanine/plumed-ves.datves">The VES_DELTA_F action with label <b>ves</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">ves.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">ves.rct</td><td>the reweighting factor c(t)</td></tr><tr><td width="5%">ves.work</td><td>the work done by the bias in one AV_STRIDE</td></tr></table></span><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FMT<span class="right"> the format that should be used to output real numbers<i></i></span></span>=%g <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=500   <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=Colvar.data <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=<b name="data/alanine/plumed-ves.datphi">phi</b>,<b name="data/alanine/plumed-ves.datpsi">psi</b>,<b name="data/alanine/plumed-ves.datves">ves.bias</b>,<b name="data/alanine/plumed-ves.datves">ves.rct</b>,<b name="data/alanine/plumed-ves.datves">ves.work</b>

<span style="display:none;" id="data/alanine/plumed-ves.dat">The PRINT action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">ENDPLUMED<span class="right">Terminate plumed input. <a href="https://www.plumed.org/doc-master/user-doc/html/ENDPLUMED" style="color:green">More details</a><i></i></span></span><span style="color:blue" class="comment">
</span></pre>
{% endraw %}
