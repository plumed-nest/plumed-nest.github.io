**Project ID:** [plumID:25.017]({{ '/' | absolute_url }}eggs/25/017/)  
**Source:** 00-Apo/2-Production/plumed_EMMI.dat  
**Originally used with PLUMED version:** 2.9  
**Stable:** [zipped raw stdout](plumed_EMMI.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_EMMI.dat.plumed.stderr.txt.zip) - [stderr](plumed_EMMI.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed_EMMI.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_EMMI.dat.plumed_master.stderr.txt.zip) - [stderr](plumed_EMMI.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/00-Apo/2-Production/plumed_EMMI.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed_EMMI.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed_EMMI.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span style="color:blue" class="comment"># if you are restarting the run, please uncomment this line</span>
<span style="color:blue" class="comment">#RESTART</span>
<span style="color:blue" class="comment"># include topology info</span>
<span class="plumedtooltip" style="color:green">MOLINFO<span class="right">This command is used to provide information on the molecules that are present in your system. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">STRUCTURE<span class="right">a file in pdb format containing a reference structure<i></i></span></span>=../1-Data/step3_input_xtc.pdb  <span class="plumedtooltip">WHOLE<span class="right"> The reference structure is whole, i<i></i></span></span>
<br/><span style="color:blue" class="comment"># define map atoms</span>
<span style="display:none;" id="data/00-Apo/2-Production/plumed_EMMI.dat">The MOLINFO action with label <b></b> calculates something</span><b name="data/00-Apo/2-Production/plumed_EMMI.datsystem-map" onclick='showPath("data/00-Apo/2-Production/plumed_EMMI.dat","data/00-Apo/2-Production/plumed_EMMI.datsystem-map","data/00-Apo/2-Production/plumed_EMMI.datsystem-map","brown")'>system-map</b>: <span class="plumedtooltip" style="color:green">GROUP<span class="right">Define a group of atoms so that a particular list of atoms can be referenced with a single label in definitions of CVs or virtual atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/GROUP" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">NDX_FILE<span class="right">the name of index file (gromacs syntax)<i></i></span></span>=<b name="data/00-Apo/2-Production/plumed_EMMI.dat">../1-Data/index.ndx</b> <span class="plumedtooltip">NDX_GROUP<span class="right">the name of the group to be imported (gromacs syntax) - first group found is used by default<i></i></span></span>=System-MAP

<span style="color:blue" class="comment"># make map atoms whole </span>
<span style="display:none;" id="data/00-Apo/2-Production/plumed_EMMI.datsystem-map">The GROUP action with label <b>system-map</b> calculates something</span><span class="plumedtooltip" style="color:green">WHOLEMOLECULES<span class="right">This action is used to rebuild molecules that can become split by the periodic boundary conditions. <a href="https://www.plumed.org/doc-master/user-doc/html/WHOLEMOLECULES" style="color:green">More details</a><i></i></span></span> ...
<span class="plumedtooltip">ADDREFERENCE<span class="right"> Define the reference position of the first atom of each entity using a PDB file<i></i></span></span> <span class="plumedtooltip">EMST<span class="right"> only for backward compatibility, as of PLUMED 2<i></i></span></span>
<span class="plumedtooltip">ENTITY0<span class="right">the atoms that make up a molecule that you wish to align<i></i></span></span>=<b name="data/00-Apo/2-Production/plumed_EMMI.datsystem-map">system-map</b> <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which molecules are reassembled<i></i></span></span>=4
... WHOLEMOLECULES
<br/><span style="color:blue" class="comment"># create EMMI score</span>
<span class="plumedtooltip" style="color:green">EMMIVOX<span class="right">Bayesian single-structure and ensemble refinement with cryo-EM maps. <a href="https://www.plumed.org/doc-master/user-doc/html/EMMIVOX" style="color:green">More details</a><i></i></span></span> ...
<span style="color:blue" class="comment"># name of this action</span>
<span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/00-Apo/2-Production/plumed_EMMI.datemmi" onclick='showPath("data/00-Apo/2-Production/plumed_EMMI.dat","data/00-Apo/2-Production/plumed_EMMI.datemmi","data/00-Apo/2-Production/plumed_EMMI.datemmi","brown")'>emmi</b>
<span style="color:blue" class="comment"># general parameters - do not change this!</span>
<span style="color:blue" class="comment"># NL_STRIDE: update neighbor list stride</span>
<span style="color:blue" class="comment"># NL_DIST_CUTOFF: distance cutoff in nm</span>
<span style="color:blue" class="comment"># NL_GAUSS_CUTOFF: cutoff based on the Gaussian sigma</span>
<span class="plumedtooltip">TEMP<span class="right">temperature<i></i></span></span>=300.0 <span class="plumedtooltip">NL_STRIDE<span class="right">neighbor list update frequency<i></i></span></span>=50 <span class="plumedtooltip">NL_DIST_CUTOFF<span class="right">neighbor list distance cutoff<i></i></span></span>=1.0 <span class="plumedtooltip">NL_GAUSS_CUTOFF<span class="right">neighbor list Gaussian sigma cutoff<i></i></span></span>=3.0
<span style="color:blue" class="comment"># define atoms for cryo-EM restraint and read experimental data</span>
<span class="plumedtooltip">ATOMS<span class="right">atoms used in the calculation of the density map, typically all heavy atoms<i></i></span></span>=<b name="data/00-Apo/2-Production/plumed_EMMI.datsystem-map">system-map</b> <span class="plumedtooltip">DATA_FILE<span class="right">file with cryo-EM map<i></i></span></span>=emd_plumed_aligned.dat
<span style="color:blue" class="comment"># info about the experimental map</span>
<span class="plumedtooltip">NORM_DENSITY<span class="right">integral of experimental density<i></i></span></span>=35666.506547 <span class="plumedtooltip">RESOLUTION<span class="right">cryo-EM map resolution<i></i></span></span>=0.197
<span style="color:blue" class="comment"># data likelihood (or noise model): Marginal</span>
<span class="plumedtooltip">SIGMA_MIN<span class="right">minimum density error<i></i></span></span>=0.2 <span class="plumedtooltip">GPU<span class="right"> calculate EMMIVOX on GPU with Libtorch<i></i></span></span>
<span style="color:blue" class="comment"># output: in production write with the frequency at which XTC/TRR are written</span>
<span class="plumedtooltip">STATUS_FILE<span class="right">write a file with all the data useful for restart<i></i></span></span>=EMMIStatus <span class="plumedtooltip">WRITE_STRIDE<span class="right">stride for writing status file<i></i></span></span>=5000
<span style="color:blue" class="comment"># comment this if you have a hetero-complex</span>
<span style="color:blue" class="comment">#BFACT_NOCHAIN</span>
<span style="color:blue" class="comment"># in production, you should sample Bfactors</span>
<span class="plumedtooltip">DBFACT<span class="right">Bfactor MC step<i></i></span></span>=0.05 <span class="plumedtooltip">MCBFACT_STRIDE<span class="right">Bfactor MC stride<i></i></span></span>=500 <span class="plumedtooltip">BFACT_SIGMA<span class="right">Bfactor sigma prior<i></i></span></span>=0.1
<span style="color:blue" class="comment"># scale factor</span>
<span class="plumedtooltip">SCALE<span class="right">scale factor<i></i></span></span>=1.200000
<span style="color:blue" class="comment"># correlation</span>
<span class="plumedtooltip">CORRELATION<span class="right"> calculate correlation coefficient<i></i></span></span>
...
<br/><span style="color:blue" class="comment"># in production, apply bias to system</span>
<span style="color:blue" class="comment"># translate into bias - updated every 2/4 time steps</span>
<span style="color:blue" class="comment"># emr: BIASVALUE ARG=emmi.scoreb STRIDE=2</span>
<span style="display:none;" id="data/00-Apo/2-Production/plumed_EMMI.datemmi">The EMMIVOX action with label <b>emmi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">emmi.scoreb</td><td>Bayesian score</td></tr><tr><td width="5%">emmi.scale</td><td>scale factor</td></tr><tr><td width="5%">emmi.offset</td><td>offset</td></tr><tr><td width="5%">emmi.accB</td><td>Bfactor MC acceptance</td></tr><tr><td width="5%">emmi.kbt</td><td>temperature in energy unit</td></tr><tr><td width="5%">emmi.corr</td><td>correlation coefficient</td></tr></table></span><b name="data/00-Apo/2-Production/plumed_EMMI.datemr" onclick='showPath("data/00-Apo/2-Production/plumed_EMMI.dat","data/00-Apo/2-Production/plumed_EMMI.datemr","data/00-Apo/2-Production/plumed_EMMI.datemr","brown")'>emr</b>: <span class="plumedtooltip" style="color:green">BIASVALUE<span class="right">Takes the value of one variable and use it as a bias <a href="https://www.plumed.org/doc-master/user-doc/html/BIASVALUE" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the scalar/vector arguments whose values will be used as a bias on the system<i></i></span></span>=<b name="data/00-Apo/2-Production/plumed_EMMI.datemmi">emmi.scoreb</b> <span class="plumedtooltip">STRIDE<span class="right">the frequency with which the forces due to the bias should be calculated<i></i></span></span>=4
<span style="color:blue" class="comment">#</span>
<span style="color:blue" class="comment"># print output to file</span>
<span style="display:none;" id="data/00-Apo/2-Production/plumed_EMMI.datemr">The BIASVALUE action with label <b>emr</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">emr.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">emr._bias</td><td>one or multiple instances of this quantity can be referenced elsewhere in the input file</td></tr></table></span><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=<b name="data/00-Apo/2-Production/plumed_EMMI.datemmi">emmi.*</b> <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=COLVAR <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=5000
</pre>
{% endraw %}
