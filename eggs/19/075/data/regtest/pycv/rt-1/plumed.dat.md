**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
**Source:** regtest/pycv/rt-1/plumed.dat  
**Originally used with PLUMED version:** 2.5.2-mod  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/regtest/pycv/rt-1/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></div>
<div class="headerBadge"><img src="https://img.shields.io/badge/with-LOAD-yellow.svg" alt="tested on master" /></div>
</div>
</div>
<pre class="plumedlisting">
<span style="color:blue" class="comment"># LOAD FILE=PythonCV.dylib</span>
<br/><b name="data/regtest/pycv/rt-1/plumed.datcv1" onclick='showPath("data/regtest/pycv/rt-1/plumed.dat","data/regtest/pycv/rt-1/plumed.datcv1","data/regtest/pycv/rt-1/plumed.datcv1","brown")'>cv1</b>: <span class="plumedtooltip" style="color:green">PYTHONCV<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> ATOMS=1,4 IMPORT=pycv FUNCTION=cv1

<b name="data/regtest/pycv/rt-1/plumed.datcv1n" onclick='showPath("data/regtest/pycv/rt-1/plumed.dat","data/regtest/pycv/rt-1/plumed.datcv1n","data/regtest/pycv/rt-1/plumed.datcv1n","brown")'>cv1n</b>: <span class="plumedtooltip" style="color:green">DISTANCE<span class="right">Calculate the distance/s between pairs of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/DISTANCE" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the pair of atom that we are calculating the distance between<i></i></span></span>=1,4

<span style="display:none;" id="data/regtest/pycv/rt-1/plumed.datcv1n">The DISTANCE action with label <b>cv1n</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">cv1n.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=colvar.out <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=*
</pre>
{% endraw %}
