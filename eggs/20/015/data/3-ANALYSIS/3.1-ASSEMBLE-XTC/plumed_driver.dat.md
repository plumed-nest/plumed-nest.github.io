**Project ID:** [plumID:20.015]({{ '/' | absolute_url }}eggs/20/015/)  
**Source:** 3-ANALYSIS/3.1-ASSEMBLE-XTC/plumed_driver.dat  
**Originally used with PLUMED version:** 2.6-dev  
**Stable:** [zipped raw stdout](plumed_driver.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_driver.dat.plumed.stderr.txt.zip) - [stderr](plumed_driver.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed_driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_driver.dat.plumed_master.stderr.txt.zip) - [stderr](plumed_driver.dat.plumed_master.stderr)  

{% raw %}
<div class="plumedpreheader">
<div class="headerInfo" id="value_details_data/3-ANALYSIS/3.1-ASSEMBLE-XTC/plumed_driver.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div class="containerBadge">
<div class="headerBadge"><a href="plumed_driver.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></div>
<div class="headerBadge"><a href="plumed_driver.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></div>
</div>
</div>
<pre class="plumedlisting">
<span style="color:blue" class="comment"># include topology info</span>
<span class="plumedtooltip" style="color:green">MOLINFO<span class="right">This command is used to provide information on the molecules that are present in your system. <a href="https://www.plumed.org/doc-master/user-doc/html/MOLINFO" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">STRUCTURE<span class="right">a file in pdb format containing a reference structure<i></i></span></span>=../../0-TOPO/step5_charmm2gmx.pdb <span class="plumedtooltip">WHOLE<span class="right"> The reference structure is whole, i<i></i></span></span>
<br/><span style="color:blue" class="comment"># define all atoms</span>
<span style="display:none;" id="data/3-ANALYSIS/3.1-ASSEMBLE-XTC/plumed_driver.dat">The MOLINFO action with label <b></b> calculates something</span><b name="data/3-ANALYSIS/3.1-ASSEMBLE-XTC/plumed_driver.datprot" onclick='showPath("data/3-ANALYSIS/3.1-ASSEMBLE-XTC/plumed_driver.dat","data/3-ANALYSIS/3.1-ASSEMBLE-XTC/plumed_driver.datprot","data/3-ANALYSIS/3.1-ASSEMBLE-XTC/plumed_driver.datprot","brown")'>prot</b>: <span class="plumedtooltip" style="color:green">GROUP<span class="right">Define a group of atoms so that a particular list of atoms can be referenced with a single label in definitions of CVs or virtual atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/GROUP" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">NDX_FILE<span class="right">the name of index file (gromacs syntax)<i></i></span></span>=<b name="data/3-ANALYSIS/3.1-ASSEMBLE-XTC/plumed_driver.dat">../../0-TOPO/index.ndx</b> <span class="plumedtooltip">NDX_GROUP<span class="right">the name of the group to be imported (gromacs syntax) - first group found is used by default<i></i></span></span>=PROT

<span style="color:blue" class="comment"># make protein whole</span>
<span style="display:none;" id="data/3-ANALYSIS/3.1-ASSEMBLE-XTC/plumed_driver.datprot">The GROUP action with label <b>prot</b> calculates something</span><span class="plumedtooltip" style="color:green">WHOLEMOLECULES<span class="right">This action is used to rebuild molecules that can become split by the periodic boundary conditions. <a href="https://www.plumed.org/doc-master/user-doc/html/WHOLEMOLECULES" style="color:green">More details</a><i></i></span></span> ...
<span class="plumedtooltip">ADDREFERENCE<span class="right"> Define the reference position of the first atom of each entity using a PDB file<i></i></span></span>
<span class="plumedtooltip">EMST<span class="right"> only for backward compatibility, as of PLUMED 2<i></i></span></span>
<span class="plumedtooltip">ENTITY0<span class="right">the atoms that make up a molecule that you wish to align<i></i></span></span>=1-6701
<span class="plumedtooltip">ENTITY1<span class="right">the atoms that make up a molecule that you wish to align<i></i></span></span>=6702-6741
... WHOLEMOLECULES
<br/><span style="color:blue" class="comment"># PRINT ATOM POSITIONS</span>
<span class="plumedtooltip" style="color:green">DUMPATOMS<span class="right">Dump selected atoms on a file. <a href="https://www.plumed.org/doc-master/user-doc/html/DUMPATOMS" style="color:green">More details</a><i></i></span></span> <span class="plumedtooltip">STRIDE<span class="right"> the frequency with which the atoms should be output<i></i></span></span>=1 <span class="plumedtooltip">FILE<span class="right">file on which to output coordinates; extension is automatically detected<i></i></span></span>=traj.gro <span class="plumedtooltip">ATOMS<span class="right">the atom indices whose positions you would like to print out<i></i></span></span>=<b name="data/3-ANALYSIS/3.1-ASSEMBLE-XTC/plumed_driver.datprot">prot</b>
</pre>
{% endraw %}
