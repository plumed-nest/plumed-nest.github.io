**Project ID:** [plumID:21.029]({{ '/' | absolute_url }}eggs/21/029/)  
**Source:** ala3/unbiased/plumed.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/ala3/unbiased/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></td></tr></table></div></div>
<pre style="width=97%;">
<div class="tooltip" style="color:green">MOLINFO<div class="right">This command is used to provide information on the molecules that are present in your system. <a href="https://www.plumed.org/doc-master/user-doc/html/_m_o_l_i_n_f_o.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">MOLTYPE<div class="right"> what kind of molecule is contained in the pdb file - usually not needed since protein/RNA/DNA are compatible<i></i></div></div>=protein <div class="tooltip">STRUCTURE<div class="right">a file in pdb format containing a reference structure<i></i></div></div>=ala3.pdb
<span style="display:none;" id="data/ala3/unbiased/plumed.dat">The MOLINFO action with label <b></b> calculates something</span><div class="tooltip" style="color:green">FLUSH<div class="right">This command instructs plumed to flush all the open files with a user specified frequency. <a href="https://www.plumed.org/doc-master/user-doc/html/_f_l_u_s_h.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">STRIDE<div class="right">the frequency with which all the open files should be flushed<i></i></div></div>=500
<br/><b name="data/ala3/unbiased/plumed.datenergy" onclick='showPath("data/ala3/unbiased/plumed.dat","data/ala3/unbiased/plumed.datenergy","data/ala3/unbiased/plumed.datenergy","black")'>energy</b><span style="display:none;" id="data/ala3/unbiased/plumed.datenergy">The ENERGY action with label <b>energy</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">energy</td><td width="5%"><font color="black">scalar</font></td><td>the internal energy</td></tr></table></span>: <div class="tooltip" style="color:green">ENERGY<div class="right">Calculate the total potential energy of the simulation box. <a href="https://www.plumed.org/doc-master/user-doc/html/_e_n_e_r_g_y.html" style="color:green">More details</a><i></i></div></div> 
<b name="data/ala3/unbiased/plumed.datphi1" onclick='showPath("data/ala3/unbiased/plumed.dat","data/ala3/unbiased/plumed.datphi1","data/ala3/unbiased/plumed.datphi1","black")'>phi1</b><span style="display:none;" id="data/ala3/unbiased/plumed.datphi1">The TORSION action with label <b>phi1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi1</td><td width="5%"><font color="black">scalar</font></td><td>the TORSION involving these atoms</td></tr></table></span>:   <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=5,7,9,15       <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<b name="data/ala3/unbiased/plumed.datpsi1" onclick='showPath("data/ala3/unbiased/plumed.dat","data/ala3/unbiased/plumed.datpsi1","data/ala3/unbiased/plumed.datpsi1","black")'>psi1</b><span style="display:none;" id="data/ala3/unbiased/plumed.datpsi1">The TORSION action with label <b>psi1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">psi1</td><td width="5%"><font color="black">scalar</font></td><td>the TORSION involving these atoms</td></tr></table></span>:   <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=7,9,15,17      <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<b name="data/ala3/unbiased/plumed.datphi2" onclick='showPath("data/ala3/unbiased/plumed.dat","data/ala3/unbiased/plumed.datphi2","data/ala3/unbiased/plumed.datphi2","black")'>phi2</b><span style="display:none;" id="data/ala3/unbiased/plumed.datphi2">The TORSION action with label <b>phi2</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi2</td><td width="5%"><font color="black">scalar</font></td><td>the TORSION involving these atoms</td></tr></table></span>:   <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=15,17,19,25    <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<b name="data/ala3/unbiased/plumed.datpsi2" onclick='showPath("data/ala3/unbiased/plumed.dat","data/ala3/unbiased/plumed.datpsi2","data/ala3/unbiased/plumed.datpsi2","black")'>psi2</b><span style="display:none;" id="data/ala3/unbiased/plumed.datpsi2">The TORSION action with label <b>psi2</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">psi2</td><td width="5%"><font color="black">scalar</font></td><td>the TORSION involving these atoms</td></tr></table></span>:   <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=17,19,25,27    <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<b name="data/ala3/unbiased/plumed.datphi3" onclick='showPath("data/ala3/unbiased/plumed.dat","data/ala3/unbiased/plumed.datphi3","data/ala3/unbiased/plumed.datphi3","black")'>phi3</b><span style="display:none;" id="data/ala3/unbiased/plumed.datphi3">The TORSION action with label <b>phi3</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi3</td><td width="5%"><font color="black">scalar</font></td><td>the TORSION involving these atoms</td></tr></table></span>:   <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=25,27,29,35    <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<b name="data/ala3/unbiased/plumed.datpsi3" onclick='showPath("data/ala3/unbiased/plumed.dat","data/ala3/unbiased/plumed.datpsi3","data/ala3/unbiased/plumed.datpsi3","black")'>psi3</b><span style="display:none;" id="data/ala3/unbiased/plumed.datpsi3">The TORSION action with label <b>psi3</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">psi3</td><td width="5%"><font color="black">scalar</font></td><td>the TORSION involving these atoms</td></tr></table></span>:   <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=27,29,35,37    <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>




<br/><div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> ...
<div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=<b name="data/ala3/unbiased/plumed.datphi1">phi1</b>,<b name="data/ala3/unbiased/plumed.datpsi1">psi1</b>,<b name="data/ala3/unbiased/plumed.datphi2">phi2</b>,<b name="data/ala3/unbiased/plumed.datpsi2">psi2</b>,<b name="data/ala3/unbiased/plumed.datphi3">phi3</b>,<b name="data/ala3/unbiased/plumed.datpsi3">psi3</b>
<div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=100
<div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=COLVAR
... PRINT
</pre>
{% endraw %}