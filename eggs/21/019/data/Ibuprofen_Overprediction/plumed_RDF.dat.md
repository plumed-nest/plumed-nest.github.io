**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
**Source:** Ibuprofen_Overprediction/plumed_RDF.dat  
**Originally used with PLUMED version:** 2.5-mod  
**Stable:** [zipped raw stdout](plumed_RDF.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_RDF.dat.plumed.stderr.txt.zip) - [stderr](plumed_RDF.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed_RDF.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_RDF.dat.plumed_master.stderr.txt.zip) - [stderr](plumed_RDF.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/Ibuprofen_Overprediction/plumed_RDF.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed_RDF.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed_RDF.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span style="color:blue" class="comment"># Define Centers of atoms (Mass-Charge file required)</span>
<b name="data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c1" onclick='showPath("data/Ibuprofen_Overprediction/plumed_RDF.dat","data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c1","data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c1","brown")'>RDF_c1</b>: <span class="plumedtooltip" style="color:green">COM<span class="right">Calculate the center of mass for a group of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/COM" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the list of atoms which are involved the virtual atom's definition<i></i></span></span>=1,2,4,6,7,8,10,11,13,16,18,20,22,26,30
<span style="display:none;" id="data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c1">The COM action with label <b>RDF_c1</b> calculates something</span><b name="data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c2" onclick='showPath("data/Ibuprofen_Overprediction/plumed_RDF.dat","data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c2","data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c2","brown")'>RDF_c2</b>: <span class="plumedtooltip" style="color:green">COM<span class="right">Calculate the center of mass for a group of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/COM" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the list of atoms which are involved the virtual atom's definition<i></i></span></span>=34,35,37,39,40,41,43,44,46,49,51,53,55,59,63
<span style="display:none;" id="data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c2">The COM action with label <b>RDF_c2</b> calculates something</span><b name="data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c3" onclick='showPath("data/Ibuprofen_Overprediction/plumed_RDF.dat","data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c3","data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c3","brown")'>RDF_c3</b>: <span class="plumedtooltip" style="color:green">COM<span class="right">Calculate the center of mass for a group of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/COM" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the list of atoms which are involved the virtual atom's definition<i></i></span></span>=67,68,70,72,73,74,76,77,79,82,84,86,88,92,96
<span style="display:none;" id="data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c3">The COM action with label <b>RDF_c3</b> calculates something</span><b name="data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c4" onclick='showPath("data/Ibuprofen_Overprediction/plumed_RDF.dat","data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c4","data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c4","brown")'>RDF_c4</b>: <span class="plumedtooltip" style="color:green">COM<span class="right">Calculate the center of mass for a group of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/COM" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the list of atoms which are involved the virtual atom's definition<i></i></span></span>=100,101,103,105,106,107,109,110,112,115,117,119,121,125,129
...
RDF_c284 COM <span class="plumedtooltip">ATOMS<span class="right">the list of atoms which are involved the virtual atom's definition<i></i></span></span>=9340,9341,9343,9345,9346,9347,9349,9350,9352,9355,9357,9359,9361,9365,9369
RDF_c285 COM <span class="plumedtooltip">ATOMS<span class="right">the list of atoms which are involved the virtual atom's definition<i></i></span></span>=9373,9374,9376,9378,9379,9380,9382,9383,9385,9388,9390,9392,9394,9398,9402
RDF_c286 COM <span class="plumedtooltip">ATOMS<span class="right">the list of atoms which are involved the virtual atom's definition<i></i></span></span>=9406,9407,9409,9411,9412,9413,9415,9416,9418,9421,9423,9425,9427,9431,9435
RDF_c287 COM <span class="plumedtooltip">ATOMS<span class="right">the list of atoms which are involved the virtual atom's definition<i></i></span></span>=9439,9440,9442,9444,9445,9446,9448,9449,9451,9454,9456,9458,9460,9464,9468
RDF_c288 COM <span class="plumedtooltip">ATOMS<span class="right">the list of atoms which are involved the virtual atom's definition<i></i></span></span>=9472,9473,9475,9477,9478,9479,9481,9482,9484,9487,9489,9491,9493,9497,9501

<span style="color:blue" class="comment"># Calculate the distances and plot distribution</span>
RDF_g GROUP <span class="plumedtooltip">ATOMS<span class="right">the list of atoms which are involved the virtual atom's definition<i></i></span></span>=<b name="data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c1">RDF_c1</b>,<b name="data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c2">RDF_c2</b>,<b name="data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c3">RDF_c3</b>,RDF_c4,...,RDF_c285,RDF_c286,RDF_c287,RDF_c288
RDF_d DISTANCES GROUP=RDF_g MORE_THAN={RATIONAL R_0=0.01 D_0=2.09 D_MAX=2.09} HISTOGRAM={TRIANGULAR NBINS=208 BANDWIDTH=0.01 UPPER=2.09 LOWER=0.01}
PRINT ARG=RDF_d.* FILE=plumed_md_RDF.dat
<span style="display:none;" id="data/Ibuprofen_Overprediction/plumed_RDF.datRDF_c4">The COM action with label <b>RDF_c4</b> calculates something</span></pre>
{% endraw %}
