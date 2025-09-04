**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
**Source:** BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat  
**Originally used with PLUMED version:** 2.8  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span class="plumedtooltip" style="color:blue"># vim:ft=plumed<span class="right">Enables syntax highlighting for PLUMED files in vim. See <a href="https://www.plumed.org/doc-master/user-doc/html/vim">here for more details. </a><i></i></span></span>
<br/><span class="plumedtooltip" style="color:green">ENVIRONMENTSIMILARITY<span class="right">Measure how similar the environment around atoms is to that found in some reference crystal structure. <a href="https://www.plumed.org/doc-master/user-doc/html/ENVIRONMENTSIMILARITY" style="color:green">More details</a><i></i></span></span> ...
 <span class="plumedtooltip">SPECIES<span class="right">this keyword is used for colvars such as coordination number<i></i></span></span>=1-972:3
 <span class="plumedtooltip">SIGMA<span class="right"> the width to use for the gaussian kernels<i></i></span></span>=0.0675
 <span class="plumedtooltip">CRYSTAL_STRUCTURE<span class="right"> Targeted crystal structure<i></i></span></span>=CUSTOM
 <span class="plumedtooltip">LABEL<span class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></span></span>=<b name="data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.datrefcv" onclick='showPath("data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat","data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.datrefcv","data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.datrefcv","brown")'>refcv</b>
 <span class="plumedtooltip">REFERENCE_1<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env1.pdb
 <span class="plumedtooltip">REFERENCE_2<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env2.pdb
 <span class="plumedtooltip">REFERENCE_3<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env3.pdb
 <span class="plumedtooltip">REFERENCE_4<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env4.pdb
 <span class="plumedtooltip">REFERENCE_5<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env5.pdb
 <span class="plumedtooltip">REFERENCE_6<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env6.pdb
 <span class="plumedtooltip">REFERENCE_7<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env7.pdb
 <span class="plumedtooltip">REFERENCE_8<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env8.pdb
 <span class="plumedtooltip">REFERENCE_9<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env9.pdb
 <span class="plumedtooltip">REFERENCE_10<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env10.pdb
 <span class="plumedtooltip">REFERENCE_11<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env11.pdb
 <span class="plumedtooltip">REFERENCE_12<span class="right">PDB files with relative distances from central atom<i></i></span></span>=env12.pdb
 <span class="plumedtooltip">MORE_THAN<span class="right">calculate the number of variables that are more than a certain target value. Options for this keyword are explained in the documentation for <a href="https://www.plumed.org/doc-master/user-doc/html/MORE_THAN">MORE_THAN</a>.<i></i></span></span>={RATIONAL R_0=0.5 NN=8 MM=16}
 <span class="plumedtooltip">MEAN<span class="right"> calculate the mean of all the quantities<i></i></span></span>
... ENVIRONMENTSIMILARITY
<br/><span style="display:none;" id="data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.datrefcv">The ENVIRONMENTSIMILARITY action with label <b>refcv</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">refcv.value</td><td>the environmental similar parameter for each of the input atoms</td></tr><tr><td width="5%">refcv.morethan</td><td>the number of colvars that have a value more than a threshold</td></tr><tr><td width="5%">refcv.mean</td><td>the mean of the colvars</td></tr></table></span><b name="data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dathh" onclick='showPath("data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat","data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dathh","data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dathh","brown")'>hh</b>: <span class="plumedtooltip" style="color:green">HISTOGRAM<span class="right">Accumulate the average probability density along a few CVs from a trajectory. <a href="https://www.plumed.org/doc-master/user-doc/html/HISTOGRAM" style="color:green">More details</a><i></i></span></span> ...
   <span class="plumedtooltip">DATA<span class="right">You should use ARG instead of this keyword which was used in older versions of PLUMED and is provided for back compatibility only<i></i></span></span>=<b name="data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.datrefcv">refcv</b>
   <span class="plumedtooltip">GRID_MIN<span class="right"> the lower bounds for the grid<i></i></span></span>=-0.5
   <span class="plumedtooltip">GRID_MAX<span class="right"> the upper bounds for the grid<i></i></span></span>=2
   <span class="plumedtooltip">GRID_BIN<span class="right">the number of bins for the grid<i></i></span></span>=1000
   <span class="plumedtooltip">BANDWIDTH<span class="right">the bandwidths for kernel density esimtation<i></i></span></span>=0.01
...
<br/><span style="display:none;" id="data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dathh">The HISTOGRAM action with label <b>hh</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">hh.value</td><td>the estimate of the histogram as a function of the argument that was obtained</td></tr></table></span><span class="plumedtooltip" style="color:green">DUMPGRID<span class="right">Output the function on the grid to a file with the PLUMED grid format. <a href="https://www.plumed.org/doc-master/user-doc/html/DUMPGRID" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">GRID<span class="right">You should use ARG instead of this keyword which was used in older versions of PLUMED and is provided for back compatibility only<i></i></span></span>=<b name="data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dathh">hh</b> <span class="plumedtooltip">FILE<span class="right"> the file on which to write the grid<i></i></span></span>=histo

<span style="display:none;" id="data/BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat">The DUMPGRID action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=500  <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=* <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=COLVAR
</pre>
{% endraw %}
