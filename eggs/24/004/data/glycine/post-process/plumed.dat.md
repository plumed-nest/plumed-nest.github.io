**Project ID:** [plumID:24.004]({{ '/' | absolute_url }}eggs/24/004/)  
**Source:** glycine/post-process/plumed.dat  
**Originally used with PLUMED version:** 2.8.1  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/glycine/post-process/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></div>
<div class="headerBadge"><img src="https://img.shields.io/badge/with-LOAD-yellow.svg" alt="tested on master" /></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:green">LOAD<span class="right">Loads a library, possibly defining new actions. <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FILE<span class="right">file to be loaded<i></i></span></span>=GraphMolNoDeriv.cpp

<span style="color:blue" class="comment"># Define groups for the CV</span>
<span style="display:none;" id="data/glycine/post-process/plumed.dat">The LOAD action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">INCLUDE<span class="right">Includes an external input file, similar to #include in C preprocessor. <a href="https://www.plumed.org/doc-master/user-doc/html/INCLUDE" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FILE<span class="right">file to be included<i></i></span></span>=<b name="data/glycine/post-process/plumed.dat">../coms_120.dat</b>
<span class="plumedtooltip" style="color:green">INCLUDE<span class="right">Includes an external input file, similar to #include in C preprocessor. <a href="https://www.plumed.org/doc-master/user-doc/html/INCLUDE" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FILE<span class="right">file to be included<i></i></span></span>=<b name="data/glycine/post-process/plumed.dat">../centers_120.dat</b>
<b name="data/glycine/post-process/plumed.datO1" onclick='showPath("data/glycine/post-process/plumed.dat","data/glycine/post-process/plumed.datO1","data/glycine/post-process/plumed.datO1","brown")'>O1</b>: <span class="plumedtooltip" style="color:green">GROUP<span class="right">Define a group of atoms so that a particular list of atoms can be referenced with a single label in definitions of CVs or virtual atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/GROUP" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the numerical indexes for the set of atoms in the group<i></i></span></span>=1-1200:10
<span style="display:none;" id="data/glycine/post-process/plumed.datO1">The GROUP action with label <b>O1</b> calculates something</span><b name="data/glycine/post-process/plumed.datO2" onclick='showPath("data/glycine/post-process/plumed.dat","data/glycine/post-process/plumed.datO2","data/glycine/post-process/plumed.datO2","brown")'>O2</b>: <span class="plumedtooltip" style="color:green">GROUP<span class="right">Define a group of atoms so that a particular list of atoms can be referenced with a single label in definitions of CVs or virtual atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/GROUP" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the numerical indexes for the set of atoms in the group<i></i></span></span>=2-1200:10
<span style="display:none;" id="data/glycine/post-process/plumed.datO2">The GROUP action with label <b>O2</b> calculates something</span><b name="data/glycine/post-process/plumed.datC" onclick='showPath("data/glycine/post-process/plumed.dat","data/glycine/post-process/plumed.datC","data/glycine/post-process/plumed.datC","brown")'>C</b>: <span class="plumedtooltip" style="color:green">GROUP<span class="right">Define a group of atoms so that a particular list of atoms can be referenced with a single label in definitions of CVs or virtual atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/GROUP" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the numerical indexes for the set of atoms in the group<i></i></span></span>=3-1200:10
<span style="display:none;" id="data/glycine/post-process/plumed.datC">The GROUP action with label <b>C</b> calculates something</span><b name="data/glycine/post-process/plumed.datCA" onclick='showPath("data/glycine/post-process/plumed.dat","data/glycine/post-process/plumed.datCA","data/glycine/post-process/plumed.datCA","brown")'>CA</b>: <span class="plumedtooltip" style="color:green">GROUP<span class="right">Define a group of atoms so that a particular list of atoms can be referenced with a single label in definitions of CVs or virtual atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/GROUP" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the numerical indexes for the set of atoms in the group<i></i></span></span>=4-1200:10
<span style="display:none;" id="data/glycine/post-process/plumed.datCA">The GROUP action with label <b>CA</b> calculates something</span><b name="data/glycine/post-process/plumed.datN" onclick='showPath("data/glycine/post-process/plumed.dat","data/glycine/post-process/plumed.datN","data/glycine/post-process/plumed.datN","brown")'>N</b>: <span class="plumedtooltip" style="color:green">GROUP<span class="right">Define a group of atoms so that a particular list of atoms can be referenced with a single label in definitions of CVs or virtual atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/GROUP" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the numerical indexes for the set of atoms in the group<i></i></span></span>=5-1200:10
 
<span style="color:blue" class="comment"># Define the CV</span>
<span style="display:none;" id="data/glycine/post-process/plumed.datN">The GROUP action with label <b>N</b> calculates something</span><span class="plumedtooltip" style="color:green">GRAPHMOLNODERIV<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> ...
 LABEL=<b name="data/glycine/post-process/plumed.datmodel" onclick='showPath("data/glycine/post-process/plumed.dat","data/glycine/post-process/plumed.datmodel","data/glycine/post-process/plumed.datmodel","brown")'>model</b>
 CENTER=COM
 START1=<b name="data/glycine/post-process/plumed.datC">C</b>
 END1=<b name="data/glycine/post-process/plumed.datCA">CA</b>
 START2=<b name="data/glycine/post-process/plumed.datN">N</b>
 END2=<b name="data/glycine/post-process/plumed.datC">C</b>
 START3=<b name="data/glycine/post-process/plumed.datN">N</b>
 END3=<b name="data/glycine/post-process/plumed.datCA">CA</b>
 START4=CHcenter
 END4=<b name="data/glycine/post-process/plumed.datCA">CA</b>
 KCUT=8
 MODEL=model-local.pt
... GRAPHMOLNODERIV
<br/><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=model.* <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=1 <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=COLVAR 
</pre>
{% endraw %}
