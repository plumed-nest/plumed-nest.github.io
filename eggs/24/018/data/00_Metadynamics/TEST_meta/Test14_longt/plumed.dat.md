**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
**Source:** 00_Metadynamics/TEST_meta/Test14_longt/plumed.dat  
**Originally used with PLUMED version:** 1.3  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/00_Metadynamics/TEST_meta/Test14_longt/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:green">HILLS<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> RESTART HEIGHT 0005 W_STRIDE 150
<span style="color:blue" class="comment">#WELLTEMPERED SIMTEMP 300 BIASFACTOR 50</span>
<br/><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> W_STRIDE 1
<br/><span style="display:none;" id="data/00_Metadynamics/TEST_meta/Test14_longt/plumed.dat">The PRINT action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">C<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span>
<span class="plumedtooltip" style="color:green">1<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> 2 
<span class="plumedtooltip" style="color:green">C<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span>
<br/><span class="plumedtooltip" style="color:green">O<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span>
 LOOP 3 83 1
<span class="plumedtooltip" style="color:green">O<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span>
<br/><span class="plumedtooltip" style="color:green">N<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span>
<span class="plumedtooltip" style="color:green">84<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> 85
<span class="plumedtooltip" style="color:green">N<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span>
<br/><span class="plumedtooltip" style="color:green">H<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span>
<span class="plumedtooltip" style="color:green">LOOP<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> 86 251 1
<span class="plumedtooltip" style="color:green">H<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span>
<br/><span class="plumedtooltip" style="color:green">SPATHCOORDTABLE<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> NSP 4 LIST C O N H NN 8 MM 14 R_0 340 340 340 283 340 340 283 340 283 265 LAMBDA 0139 SIGMA 003
                                   
<span class="plumedtooltip" style="color:green">ZPATHCOORDTABLE<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> NSP 4 LIST C O N H NN 8 MM 14 R_0 340 340 340 283 340 340 283 340 283 265 LAMBDA 0139 SIGMA 02
<br/><span style="color:blue" class="comment"># dist C-C</span>
<span class="plumedtooltip" style="color:green">DISTANCE<span class="right">Calculate the distance/s between pairs of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/DISTANCE" style="color:green">More details</a><i></i></span></span> LIST 1 2
<span style="color:blue" class="comment"># dist N-N</span>
<span class="plumedtooltip" style="color:green">DISTANCE<span class="right">Calculate the distance/s between pairs of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/DISTANCE" style="color:green">More details</a><i></i></span></span> LIST 84 85
<span style="color:blue" class="comment"># dist C-N</span>
<span class="plumedtooltip" style="color:green">DISTANCE<span class="right">Calculate the distance/s between pairs of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/DISTANCE" style="color:green">More details</a><i></i></span></span> LIST 2 84
<span class="plumedtooltip" style="color:green">DISTANCE<span class="right">Calculate the distance/s between pairs of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/DISTANCE" style="color:green">More details</a><i></i></span></span> LIST 2 85
<span class="plumedtooltip" style="color:green">DISTANCE<span class="right">Calculate the distance/s between pairs of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/DISTANCE" style="color:green">More details</a><i></i></span></span> LIST 1 84
<span class="plumedtooltip" style="color:green">DISTANCE<span class="right">Calculate the distance/s between pairs of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/DISTANCE" style="color:green">More details</a><i></i></span></span> LIST 1 85
<br/><span style="color:blue" class="comment">#UWALL CV 2 LIMIT 1. KAPPA 0.05 EXP 2</span>
<br/><span class="plumedtooltip" style="color:green">UWALL<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> CV 3 LIMIT 10 KAPPA 001 EXP 2
<span class="plumedtooltip" style="color:green">UWALL<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> CV 4 LIMIT 10 KAPPA 001 EXP 2
<span class="plumedtooltip" style="color:green">UWALL<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> CV 5 LIMIT 10 KAPPA 001 EXP 2
<span class="plumedtooltip" style="color:green">UWALL<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> CV 6 LIMIT 10 KAPPA 001 EXP 2
<span class="plumedtooltip" style="color:green">UWALL<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> CV 7 LIMIT 10 KAPPA 001 EXP 2
<span class="plumedtooltip" style="color:green">UWALL<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> CV 8 LIMIT 10 KAPPA 001 EXP 2
<span class="plumedtooltip" style="color:green">ENDMETA<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span>
</pre>
{% endraw %}
