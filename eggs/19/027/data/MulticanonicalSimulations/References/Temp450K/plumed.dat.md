**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
**Source:** MulticanonicalSimulations/References/Temp450K/plumed.dat  
**Originally used with PLUMED version:** 2.4-dev  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/MulticanonicalSimulations/References/Temp450K/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:blue"># vim:ft=plumed<span class="right">Enables syntax highlighting for PLUMED files in vim. See <a href="https://www.plumed.org/doc-master/user-doc/html/vim">here for more details. </a><i></i></span></span>
<br/><span class="plumedtooltip" style="color:green">UNITS<span class="right">This command sets the internal units for the code. <a href="https://www.plumed.org/doc-master/user-doc/html/UNITS" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">LENGTH<span class="right">the units of lengths<i></i></span></span>=A

<span style="display:none;" id="data/MulticanonicalSimulations/References/Temp450K/plumed.dat">The UNITS action with label <b></b> calculates something</span><b name="data/MulticanonicalSimulations/References/Temp450K/plumed.datenergy" onclick='showPath("data/MulticanonicalSimulations/References/Temp450K/plumed.dat","data/MulticanonicalSimulations/References/Temp450K/plumed.datenergy","data/MulticanonicalSimulations/References/Temp450K/plumed.datenergy","brown")'>energy</b>: <span class="plumedtooltip" style="color:green">ENERGY<span class="right">Calculate the total potential energy of the simulation box. <a href="https://www.plumed.org/doc-master/user-doc/html/ENERGY" style="color:green">More details</a><i></i></span></span>
<br/><span style="display:none;" id="data/MulticanonicalSimulations/References/Temp450K/plumed.datenergy">The ENERGY action with label <b>energy</b> calculates something</span><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=* <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=COLVAR <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=500
</pre>
{% endraw %}
