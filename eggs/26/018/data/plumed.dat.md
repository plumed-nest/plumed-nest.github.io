**Project ID:** [plumID:26.018]({{ '/' | absolute_url }}eggs/26/018/)  
**Source:** plumed.dat  
**Originally used with PLUMED version:** 2.9  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedInputContainer">
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
<div class="headerBadge"><img src="https://img.shields.io/badge/with-LOAD-yellow.svg" alt="tested on master" /></div>
</div>
</div>
<pre class="plumedlisting">
<span style="color:blue" class="comment"># PLUMED 2.10 or later. The source module includes seams-core v2.14.0.</span>
<span class="plumedtooltip" style="color:green">UNITS<span class="right">This command sets the internal units for the code. <a href="https://www.plumed.org/doc-master/user-doc/html/UNITS" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">LENGTH<span class="right">the units of lengths<i></i></span></span>=A
<span style="display:none;" id="data/plumed.dat">The UNITS action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">LOAD<span class="right">Loads a library, possibly defining new actions. <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">FILE<span class="right">file to be loaded<i></i></span></span>=dseams_plumed.cpp

<span style="color:blue" class="comment"># Cubic-diamond ice</span>
<b name="data/plumed.datice" onclick='showPath("data/plumed.dat","data/plumed.datice","data/plumed.datice","brown")'>ice</b>: <span class="plumedtooltip" style="color:green">DSEAMS_CAGES<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> ATOMS=1-512 CUTOFF=3.5 CANDIDATE=5.5 K=4 LENGTH_SCALE=1 COMPLETE
<span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=ice.nice,ice.nmax,ice.nclus,ice.nic,ice.nih,ice.chillice,ice.chillmax <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=1 <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=ICE <span class="plumedtooltip">FMT<span class="right"> the format that should be used to output real numbers<i></i></span></span>=%8.0f

<span style="color:blue" class="comment"># Two ions replacing water sites in a second cubic-diamond lattice</span>
<b name="data/plumed.datbrine" onclick='showPath("data/plumed.dat","data/plumed.datbrine","data/plumed.datbrine","brown")'>brine</b>: <span class="plumedtooltip" style="color:green">DSEAMS_CAGES<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> ATOMS=513-1022 IONS=1023-1024 ION_CUTOFF=3.5 CUTOFF=3.5 CANDIDATE=5.5 K=4 LENGTH_SCALE=1 COMPLETE
<span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=brine.nice,brine.nmax,brine.nionice,brine.nionfront,brine.nionliq <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=1 <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=BRINE <span class="plumedtooltip">FMT<span class="right"> the format that should be used to output real numbers<i></i></span></span>=%8.0f

<span style="color:blue" class="comment"># Periodic cubic cages with one guest in each of 64 cages</span>
<b name="data/plumed.dathyd" onclick='showPath("data/plumed.dat","data/plumed.dathyd","data/plumed.dathyd","brown")'>hyd</b>: <span class="plumedtooltip" style="color:green">DSEAMS_CAGES<span class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/LOAD" style="color:green">More details</a><i></i></span></span> ATOMS=1025-1536 GUESTS=1537-1600 CUTOFF=3.5 CANDIDATE=4.8 K=6 LENGTH_SCALE=1 SIGNATURE=4:6 GUEST_RADIUS=3.0
<span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=hyd.ncages,hyd.noccupied,hyd.nmultiple,hyd.nfreeguest <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=1 <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=HYDRATE <span class="plumedtooltip">FMT<span class="right"> the format that should be used to output real numbers<i></i></span></span>=%8.0f
</pre></div>

{% endraw %}
