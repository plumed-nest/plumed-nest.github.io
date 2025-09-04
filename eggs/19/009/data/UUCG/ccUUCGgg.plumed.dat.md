**Project ID:** [plumID:19.009]({{ '/' | absolute_url }}eggs/19/009/)  
**Source:** UUCG/ccUUCGgg.plumed.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [zipped raw stdout](ccUUCGgg.plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](ccUUCGgg.plumed.dat.plumed.stderr.txt.zip) - [stderr](ccUUCGgg.plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](ccUUCGgg.plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ccUUCGgg.plumed.dat.plumed_master.stderr.txt.zip) - [stderr](ccUUCGgg.plumed.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/UUCG/ccUUCGgg.plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="ccUUCGgg.plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="ccUUCGgg.plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span style="color:blue" class="comment"># RESTART</span>
<span class="plumedtooltip" style="color:green">MOLINFO<span class="right">This command is used to provide information on the molecules that are present in your system. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">STRUCTURE<span class="right">a file in pdb format containing a reference structure<i></i></span></span>=UUCG_8_L.pdb
<span style="display:none;" id="data/UUCG/ccUUCGgg.plumed.dat">The MOLINFO action with label <b></b> calculates something</span><span class="plumedtooltip" style="color:green">WHOLEMOLECULES<span class="right">This action is used to rebuild molecules that can become split by the periodic boundary conditions. <a href="https://www.plumed.org/doc-master/user-doc/html/WHOLEMOLECULES" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ENTITY0<span class="right">the atoms that make up a molecule that you wish to align<i></i></span></span>=1-254

<b name="data/UUCG/ccUUCGgg.plumed.date0" onclick='showPath("data/UUCG/ccUUCGgg.plumed.dat","data/UUCG/ccUUCGgg.plumed.date0","data/UUCG/ccUUCGgg.plumed.date0","brown")'>e0</b>: <span class="plumedtooltip" style="color:green">ERMSD<span class="right">Calculate eRMSD with respect to a reference structure. <a href="https://www.plumed.org/doc-master/user-doc/html/ERMSD" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the list of atoms (use lcs)<i></i></span></span>=<span class="plumedtooltip">@lcs-1<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 1. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-2<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 2. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-3<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 3. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-4<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 4. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-5<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 5. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-6<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 6. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-7<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 7. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-8<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 8. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span> <span class="plumedtooltip">REFERENCE<span class="right">a file in pdb format containing the reference structure and the atoms involved in the CV<i></i></span></span>=UUCG_8_H.pdb
<span style="display:none;" id="data/UUCG/ccUUCGgg.plumed.date0">The ERMSD action with label <b>e0</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">e0.value</td><td>the eRMSD between the instantaneous structure and the reference structure that was input</td></tr></table></span><b name="data/UUCG/ccUUCGgg.plumed.date3" onclick='showPath("data/UUCG/ccUUCGgg.plumed.dat","data/UUCG/ccUUCGgg.plumed.date3","data/UUCG/ccUUCGgg.plumed.date3","brown")'>e3</b>: <span class="plumedtooltip" style="color:green">ERMSD<span class="right">Calculate eRMSD with respect to a reference structure. <a href="https://www.plumed.org/doc-master/user-doc/html/ERMSD" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the list of atoms (use lcs)<i></i></span></span>=<span class="plumedtooltip">@lcs-1<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 1. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-2<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 2. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-3<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 3. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-4<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 4. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-5<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 5. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-6<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 6. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-7<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 7. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-8<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 8. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span> <span class="plumedtooltip">REFERENCE<span class="right">a file in pdb format containing the reference structure and the atoms involved in the CV<i></i></span></span>=UUCG_8_L.pdb

<span style="display:none;" id="data/UUCG/ccUUCGgg.plumed.date3">The ERMSD action with label <b>e3</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">e3.value</td><td>the eRMSD between the instantaneous structure and the reference structure that was input</td></tr></table></span><b name="data/UUCG/ccUUCGgg.plumed.datee3" onclick='showPath("data/UUCG/ccUUCGgg.plumed.dat","data/UUCG/ccUUCGgg.plumed.datee3","data/UUCG/ccUUCGgg.plumed.datee3","brown")'>ee3</b>: <span class="plumedtooltip" style="color:green">ERMSD<span class="right">Calculate eRMSD with respect to a reference structure. <a href="https://www.plumed.org/doc-master/user-doc/html/ERMSD" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ATOMS<span class="right">the list of atoms (use lcs)<i></i></span></span>=<span class="plumedtooltip">@lcs-1<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 1. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-2<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 2. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-3<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 3. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-4<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 4. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-5<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 5. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-6<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 6. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-7<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 7. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span>,<span class="plumedtooltip">@lcs-8<span class="right">an ordered triplet of atoms on the 6-membered ring of the nucleobase in residue 8. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO">Click here</a> for more information. <i></i></span></span> <span class="plumedtooltip">REFERENCE<span class="right">a file in pdb format containing the reference structure and the atoms involved in the CV<i></i></span></span>=UUCG_8_L.pdb <span class="plumedtooltip">CUTOFF<span class="right"> only pairs of atoms closer than CUTOFF are considered in the calculation<i></i></span></span>=3.2

<span style="display:none;" id="data/UUCG/ccUUCGgg.plumed.datee3">The ERMSD action with label <b>ee3</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">ee3.value</td><td>the eRMSD between the instantaneous structure and the reference structure that was input</td></tr></table></span><b name="data/UUCG/ccUUCGgg.plumed.datr0" onclick='showPath("data/UUCG/ccUUCGgg.plumed.dat","data/UUCG/ccUUCGgg.plumed.datr0","data/UUCG/ccUUCGgg.plumed.datr0","brown")'>r0</b>: <span class="plumedtooltip" style="color:green">RMSD<span class="right">Calculate the RMSD with respect to a reference structure. <a href="https://www.plumed.org/doc-master/user-doc/html/RMSD" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">REFERENCE<span class="right">a file in pdb format containing the reference structure and the atoms involved in the CV<i></i></span></span>=UUCG_8_H.pdb <span class="plumedtooltip">TYPE<span class="right"> the manner in which RMSD alignment is performed<i></i></span></span>=OPTIMAL
<span style="display:none;" id="data/UUCG/ccUUCGgg.plumed.datr0">The RMSD action with label <b>r0</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">r0.value</td><td>the RMSD distance between the instaneous structure and the reference structure/s that were input</td></tr></table></span><b name="data/UUCG/ccUUCGgg.plumed.datr3" onclick='showPath("data/UUCG/ccUUCGgg.plumed.dat","data/UUCG/ccUUCGgg.plumed.datr3","data/UUCG/ccUUCGgg.plumed.datr3","brown")'>r3</b>: <span class="plumedtooltip" style="color:green">RMSD<span class="right">Calculate the RMSD with respect to a reference structure. <a href="https://www.plumed.org/doc-master/user-doc/html/RMSD" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">REFERENCE<span class="right">a file in pdb format containing the reference structure and the atoms involved in the CV<i></i></span></span>=UUCG_8_L.pdb <span class="plumedtooltip">TYPE<span class="right"> the manner in which RMSD alignment is performed<i></i></span></span>=OPTIMAL


<span style="display:none;" id="data/UUCG/ccUUCGgg.plumed.datr3">The RMSD action with label <b>r3</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">r3.value</td><td>the RMSD distance between the instaneous structure and the reference structure/s that were input</td></tr></table></span><b name="data/UUCG/ccUUCGgg.plumed.datmetad" onclick='showPath("data/UUCG/ccUUCGgg.plumed.dat","data/UUCG/ccUUCGgg.plumed.datmetad","data/UUCG/ccUUCGgg.plumed.datmetad","brown")'>metad</b>: <span class="plumedtooltip" style="color:green">METAD<span class="right">Used to performed metadynamics on one or more collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/METAD" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the scalars on which the bias will act<i></i></span></span>=<b name="data/UUCG/ccUUCGgg.plumed.datee3">ee3</b> <span class="plumedtooltip">PACE<span class="right">the frequency for hill addition<i></i></span></span>=500000001 <span class="plumedtooltip">HEIGHT<span class="right">the heights of the Gaussian hills<i></i></span></span>=0.0 <span class="plumedtooltip">SIGMA<span class="right">the widths of the Gaussian hills<i></i></span></span>=0.1 <span class="plumedtooltip">FILE<span class="right"> a file in which the list of added hills is stored<i></i></span></span>=HILLS_avg_5 <span class="plumedtooltip">TEMP<span class="right">the system temperature - this is only needed if you are doing well-tempered metadynamics<i></i></span></span>=300.882 <span class="plumedtooltip">BIASFACTOR<span class="right">use well tempered metadynamics and use this bias factor<i></i></span></span>=15 <span class="plumedtooltip">GRID_MIN<span class="right">the lower bounds for the grid<i></i></span></span>=0.0 <span class="plumedtooltip">GRID_MAX<span class="right">the upper bounds for the grid<i></i></span></span>=5.0 <span class="plumedtooltip">GRID_BIN<span class="right">the number of bins for the grid<i></i></span></span>=250

<span style="display:none;" id="data/UUCG/ccUUCGgg.plumed.datmetad">The METAD action with label <b>metad</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">metad.bias</td><td>the instantaneous value of the bias potential</td></tr></table></span><span class="plumedtooltip" style="color:green">PRINT<span class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/PRINT" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">ARG<span class="right">the labels of the values that you would like to print to the file<i></i></span></span>=<b name="data/UUCG/ccUUCGgg.plumed.date3">e3</b>,<b name="data/UUCG/ccUUCGgg.plumed.datee3">ee3</b>,<b name="data/UUCG/ccUUCGgg.plumed.date0">e0</b>,<b name="data/UUCG/ccUUCGgg.plumed.datr3">r3</b>,<b name="data/UUCG/ccUUCGgg.plumed.datr0">r0</b>,<b name="data/UUCG/ccUUCGgg.plumed.datmetad">metad.bias</b> <span class="plumedtooltip">FILE<span class="right">the name of the file on which to output these quantities<i></i></span></span>=colvar_5 <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the quantities of interest should be output<i></i></span></span>=1

<span class="plumedtooltip" style="color:green">ENDPLUMED<span class="right">Terminate plumed input. <a href="https://www.plumed.org/doc-master/user-doc/html/ENDPLUMED" style="color:green">More details</a><i></i></span></span><span style="color:blue" class="comment">

# histograms below are computed using PLUMED 2.3 syntax

HISTOGRAM ...
REWEIGHT_BIAS
ARG=e3
TEMP=300.882
USE_ALL_DATA
UNNORMALIZED
GRID_MIN=0
GRID_MAX=3
GRID_BIN=250
RESTART=NO
BANDWIDTH=0.0075
GRID_WFILE=fes_ermsd_5_0
UPDATE_FROM=200000
UPDATE_UNTIL=400000
... HISTOGRAM

HISTOGRAM ...
REWEIGHT_BIAS
ARG=e3
TEMP=300.882
USE_ALL_DATA
UNNORMALIZED
GRID_MIN=0
GRID_MAX=3
GRID_BIN=250
RESTART=NO
BANDWIDTH=0.0075
GRID_WFILE=fes_ermsd_5_1
UPDATE_FROM=400000
UPDATE_UNTIL=600000
... HISTOGRAM


HISTOGRAM ...
REWEIGHT_BIAS
ARG=e3
TEMP=300.882
USE_ALL_DATA
UNNORMALIZED
GRID_MIN=0
GRID_MAX=3
GRID_BIN=250
RESTART=NO
BANDWIDTH=0.0075
GRID_WFILE=fes_ermsd_5_2
UPDATE_FROM=600000
UPDATE_UNTIL=800000
... HISTOGRAM


HISTOGRAM ...
REWEIGHT_BIAS
ARG=e3
TEMP=300.882
USE_ALL_DATA
UNNORMALIZED
GRID_MIN=0
GRID_MAX=3
GRID_BIN=250
RESTART=NO
BANDWIDTH=0.0075
GRID_WFILE=fes_ermsd_5_3
UPDATE_FROM=800000
UPDATE_UNTIL=1000000
... HISTOGRAM

ENDPLUMED
################################

HISTOGRAM ...
REWEIGHT_BIAS
ARG=r3
TEMP=300.882
USE_ALL_DATA
UNNORMALIZED
GRID_MIN=0
GRID_MAX=1
GRID_BIN=250
RESTART=NO
BANDWIDTH=0.0025
GRID_WFILE=fes_rmsd_5_0
UPDATE_FROM=0
UPDATE_UNTIL=250000
... HISTOGRAM

HISTOGRAM ...
REWEIGHT_BIAS
ARG=r3
TEMP=300.882
USE_ALL_DATA
UNNORMALIZED
GRID_MIN=0
GRID_MAX=1
GRID_BIN=250
RESTART=NO
BANDWIDTH=0.0025
GRID_WFILE=fes_rmsd_5_1
UPDATE_FROM=250000
UPDATE_UNTIL=500000
... HISTOGRAM


HISTOGRAM ...
REWEIGHT_BIAS
ARG=r3
TEMP=300.882
USE_ALL_DATA
UNNORMALIZED
GRID_MIN=0
GRID_MAX=1
GRID_BIN=250
RESTART=NO
BANDWIDTH=0.0025
GRID_WFILE=fes_rmsd_5_2
UPDATE_FROM=500000
UPDATE_UNTIL=750000
... HISTOGRAM


HISTOGRAM ...
REWEIGHT_BIAS
ARG=r3
TEMP=300.882
USE_ALL_DATA
UNNORMALIZED
GRID_MIN=0
GRID_MAX=1
GRID_BIN=250
RESTART=NO
BANDWIDTH=0.0025
GRID_WFILE=fes_rmsd_5_3
UPDATE_FROM=750000
UPDATE_UNTIL=1000000
... HISTOGRAM
</span></pre>
{% endraw %}
