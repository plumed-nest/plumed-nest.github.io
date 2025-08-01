**Project ID:** [plumID:19.068]({{ '/' | absolute_url }}eggs/19/068/)  
**Source:** ala2/plumed-opes.dat  
**Originally used with PLUMED version:** 2.7  
**Stable:** [zipped raw stdout](plumed-opes.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-opes.dat.plumed.stderr.txt.zip) - [stderr](plumed-opes.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed-opes.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-opes.dat.plumed_master.stderr.txt.zip) - [stderr](plumed-opes.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/ala2/plumed-opes.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed-opes.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed-opes.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:blue"># vim:ft=plumed<span class="right">Enables syntax highlighting for PLUMED files in vim. See <a href="https://www.plumed.org/doc-master/user-doc/html/vim">here for more details. </a><i></i></span></span>
<br/><b name="data/ala2/plumed-opes.datphi" onclick='showPath("data/ala2/plumed-opes.dat","data/ala2/plumed-opes.datphi","data/ala2/plumed-opes.datphi","brown")'>phi</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=5,7,9,15
<span style="display:none;" id="data/ala2/plumed-opes.datphi">The TORSION action with label <b>phi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/ala2/plumed-opes.datpsi" onclick='showPath("data/ala2/plumed-opes.dat","data/ala2/plumed-opes.datpsi","data/ala2/plumed-opes.datpsi","brown")'>psi</b>: <span class="plumedtooltip" style="color:green">TORSION<span class="right">Calculate one or multiple torsional angles. <a href="https://www.plumed.org/doc-master/user-doc/html/TORSION" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the four atoms involved in the torsional angle<i></i></span></span>=7,9,15,17

<span style="display:none;" id="data/ala2/plumed-opes.datpsi">The TORSION action with label <b>psi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">psi.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/ala2/plumed-opes.datopes" onclick='showPath("data/ala2/plumed-opes.dat","data/ala2/plumed-opes.datopes","data/ala2/plumed-opes.datopes","brown")'>opes</b>: <span class="plumedtooltip" style="color:green">OPES_METAD<span class="right">On-the-fly probability enhanced sampling with metadynamics-like target distribution. <a href="https://www.plumed.org/doc-master/user-doc/html/OPES_METAD" style="color:green">More details</a><i></i></span></span> ...
  <span class="plumedtooltip">ARG<span class="right">the labels of the scalars on which the bias will act<i></i></span></span>=<b name="data/ala2/plumed-opes.datphi">phi</b>,<b name="data/ala2/plumed-opes.datpsi">psi</b>
  <span class="plumedtooltip">FILE<span class="right"> a file in which the list of all deposited kernels is stored<i></i></span></span>=Kernels.data
  <span class="plumedtooltip">TEMP<span class="right"> temperature<i></i></span></span>=300.0
  <span class="plumedtooltip">PACE<span class="right">the frequency for kernel deposition<i></i></span></span>=500
  <span class="plumedtooltip">SIGMA<span class="right"> the initial widths of the kernels<i></i></span></span>=0.15,0.15
  <span class="plumedtooltip">BARRIER<span class="right">the free energy barrier to be overcome<i></i></span></span>=50
  <span class="plumedtooltip">BIASFACTOR<span class="right">the gamma bias factor used for the well-tempered target distribution<i></i></span></span>=10
  <span class="plumedtooltip">STATE_WFILE<span class="right">write to this file the compressed kernels and all the info needed to RESTART the simulation<i></i></span></span>=State.data
  <span class="plumedtooltip">STATE_WSTRIDE<span class="right">number of MD steps between writing the STATE_WFILE<i></i></span></span>=10000
  <span class="plumedtooltip">STORE_STATES<span class="right"> append to STATE_WFILE instead of ovewriting it each time<i></i></span></span>
...
<br/><span style="display:none;" id="data/ala2/plumed-opes.datopes">The OPES_METAD action with label <b>opes</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">opes.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">opes.rct</td><td>estimate of c(t)</td></tr><tr><td width="5%">opes.zed</td><td>estimate of Z_n</td></tr><tr><td width="5%">opes.neff</td><td>effective sample size</td></tr><tr><td width="5%">opes.nker</td><td>total number of compressed kernels used to represent the bias</td></tr></table></span><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FMT<span class="right"> the format that should be used to output real numbers<i></i></span></span>=%g <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=500 <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=Colvar.data <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=<b name="data/ala2/plumed-opes.datphi">phi</b>,<b name="data/ala2/plumed-opes.datpsi">psi</b>,<b name="data/ala2/plumed-opes.datopes">opes.*</b>

<span style="display:none;" id="data/ala2/plumed-opes.dat">The PRINT action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">ENDPLUMED<span class="right">Terminate plumed input. <a href="https://www.plumed.org/doc-master/user-doc/html/ENDPLUMED" style="color:green">More details</a><i></i></span></span><span style="color:blue" class="comment">

A slightly better performing result can be obtained with the following simpler input:

  opes: OPES_METAD ARG=phi,psi PACE=50 BARRIER=50 NLIST

but it was not used, to have a more fair comparison with standard metadynamics ala2 simulations.
(if not set, SIGMA is chosen adaptively, similarly to METAD ADAPTIVE=DIFF)
</span></pre>
{% endraw %}
