**Project ID:** [plumID:21.033]({{ '/' | absolute_url }}eggs/21/033/)  
**Source:** outside_path/plumed.2.dat  
**Originally used with PLUMED version:** 2.6  
**Stable:** [zipped raw stdout](plumed.2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.2.dat.plumed.stderr.txt.zip) - [stderr](plumed.2.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.2.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.2.dat.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/outside_path/plumed.2.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="plumed.2.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="plumed.2.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></td></tr><tr><td style="padding:1px"><img src="https://img.shields.io/badge/with-LOAD-yellow.svg" alt="tested on master" /></td></tr>
</table></div></div>
<pre style="width=97%;">
<span id="data/outside_path/plumed.2.dat../base.dat_short"><div class="tooltip" style="color:green">INCLUDE<div class="right">Includes an external input file, similar to #include in C preprocessor. <a href="https://www.plumed.org/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">More details</a>. Show <a class="toggler" href='javascript:;' onclick='toggleDisplay("data/outside_path/plumed.2.dat../base.dat");'>included file</a><i></i></div></div> <div class="tooltip">FILE<div class="right">file to be included<i></i></div></div>=<a class="toggler" href='javascript:;' onclick='toggleDisplay("data/outside_path/plumed.2.dat../base.dat");'>../base.dat</a>
</span><span id="data/outside_path/plumed.2.dat../base.dat_long" style="display:none;"><span style="color:blue" class="comment"># The command:
</span><span class="toggler" style="color:red" onclick='toggleDisplay("data/outside_path/plumed.2.dat../base.dat")'># INCLUDE FILE=../base.dat
</span><span style="color:blue" class="comment"># ensures PLUMED loads the contents of the file called ../base.dat</span>
<span style="color:blue" class="comment"># The contents of this file are shown below (click the red comment to hide them).</span>
<span style="display:none;" id="data/outside_path/plumed.2.dat../base.dat">The INCLUDE action with label <b>../base.dat</b> calculates something</span><div class="tooltip" style="color:green">LOAD<div class="right">Loads a library, possibly defining new actions. <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">FILE<div class="right">file to be loaded<i></i></div></div>=../PathCV.cpp
<br/><span style="color:blue" class="comment"># set units</span>
<span style="display:none;" id="data/outside_path/plumed.2.dat">The LOAD action with label <b></b> calculates something</span><div class="tooltip" style="color:green">UNITS<div class="right">This command sets the internal units for the code. <a href="https://www.plumed.org/doc-master/user-doc/html/_u_n_i_t_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">LENGTH<div class="right">the units of lengths<i></i></div></div>=A <div class="tooltip">TIME<div class="right">the units of time<i></i></div></div>=ps <div class="tooltip">ENERGY<div class="right">the units of energy<i></i></div></div>=kcal/mol
<div class="tooltip" style="color:green">WHOLEMOLECULES<div class="right">This action is used to rebuild molecules that can become split by the periodic boundary conditions. <a href="https://www.plumed.org/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ENTITY0<div class="right">the atoms that make up a molecule that you wish to align<i></i></div></div>=1-762
<br/><span style="color:blue" class="comment"># define centers of mass</span>
<b name="data/outside_path/plumed.2.datp1" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datp1","data/outside_path/plumed.2.datp1","brown")'>p1</b>: <div class="tooltip" style="color:green">CENTER<div class="right">Calculate the center for a group of atoms, with arbitrary weights. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_e_n_t_e_r.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the group of atoms that you are calculating the Gyration Tensor for<i></i></div></div>=519,520,522,523,524,525,528,529,531,532,234,235,237,238,242,243,244,246,247 <div class="tooltip">MASS<div class="right"> calculate the center of mass<i></i></div></div>
<span style="display:none;" id="data/outside_path/plumed.2.datp1">The CENTER action with label <b>p1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p1.value</td><td>the position of the center of mass</td></tr></table></span><b name="data/outside_path/plumed.2.datp2" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datp2","data/outside_path/plumed.2.datp2","brown")'>p2</b>: <div class="tooltip" style="color:green">CENTER<div class="right">Calculate the center for a group of atoms, with arbitrary weights. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_e_n_t_e_r.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the group of atoms that you are calculating the Gyration Tensor for<i></i></div></div>=455,456,458,459,460,461,464,465,467,468,298,299,301,302,306,307,308,310,311 <div class="tooltip">MASS<div class="right"> calculate the center of mass<i></i></div></div>
<span style="display:none;" id="data/outside_path/plumed.2.datp2">The CENTER action with label <b>p2</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p2.value</td><td>the position of the center of mass</td></tr></table></span><b name="data/outside_path/plumed.2.datp1p2" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datp1p2","data/outside_path/plumed.2.datp1p2","brown")'>p1p2</b>: <div class="tooltip" style="color:green">CENTER<div class="right">Calculate the center for a group of atoms, with arbitrary weights. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_e_n_t_e_r.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the group of atoms that you are calculating the Gyration Tensor for<i></i></div></div>=519,520,522,523,524,525,528,529,531,532,234,235,237,238,242,243,244,246,247,455,456,458,459,460,461,464,465,467,468,298,299,301,302,306,307,308,310,311 <div class="tooltip">MASS<div class="right"> calculate the center of mass<i></i></div></div>
<span style="display:none;" id="data/outside_path/plumed.2.datp1p2">The CENTER action with label <b>p1p2</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p1p2.value</td><td>the position of the center of mass</td></tr></table></span><b name="data/outside_path/plumed.2.datp1_prime" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datp1_prime","data/outside_path/plumed.2.datp1_prime","brown")'>p1_prime</b>: <div class="tooltip" style="color:green">CENTER<div class="right">Calculate the center for a group of atoms, with arbitrary weights. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_e_n_t_e_r.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the group of atoms that you are calculating the Gyration Tensor for<i></i></div></div>=519,520,522,523,524,525,528,529,531,532 <div class="tooltip">MASS<div class="right"> calculate the center of mass<i></i></div></div>
<span style="display:none;" id="data/outside_path/plumed.2.datp1_prime">The CENTER action with label <b>p1_prime</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p1_prime.value</td><td>the position of the center of mass</td></tr></table></span><b name="data/outside_path/plumed.2.datp2_prime" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datp2_prime","data/outside_path/plumed.2.datp2_prime","brown")'>p2_prime</b>: <div class="tooltip" style="color:green">CENTER<div class="right">Calculate the center for a group of atoms, with arbitrary weights. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_e_n_t_e_r.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the group of atoms that you are calculating the Gyration Tensor for<i></i></div></div>=455,456,458,459,460,461,464,465,467,468 <div class="tooltip">MASS<div class="right"> calculate the center of mass<i></i></div></div>
<span style="display:none;" id="data/outside_path/plumed.2.datp2_prime">The CENTER action with label <b>p2_prime</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p2_prime.value</td><td>the position of the center of mass</td></tr></table></span><b name="data/outside_path/plumed.2.datp3" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datp3","data/outside_path/plumed.2.datp3","brown")'>p3</b>:  <div class="tooltip" style="color:green">CENTER<div class="right">Calculate the center for a group of atoms, with arbitrary weights. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_e_n_t_e_r.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the group of atoms that you are calculating the Gyration Tensor for<i></i></div></div>=506,507,508,509,510 <div class="tooltip">MASS<div class="right"> calculate the center of mass<i></i></div></div>
<span style="display:none;" id="data/outside_path/plumed.2.datp3">The CENTER action with label <b>p3</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p3.value</td><td>the position of the center of mass</td></tr></table></span><b name="data/outside_path/plumed.2.datp4" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datp4","data/outside_path/plumed.2.datp4","brown")'>p4</b>:  <div class="tooltip" style="color:green">CENTER<div class="right">Calculate the center for a group of atoms, with arbitrary weights. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_e_n_t_e_r.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the group of atoms that you are calculating the Gyration Tensor for<i></i></div></div>=474,475,476,477,478 <div class="tooltip">MASS<div class="right"> calculate the center of mass<i></i></div></div>
<span style="display:none;" id="data/outside_path/plumed.2.datp4">The CENTER action with label <b>p4</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p4.value</td><td>the position of the center of mass</td></tr></table></span><b name="data/outside_path/plumed.2.datp5" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datp5","data/outside_path/plumed.2.datp5","brown")'>p5</b>:  <div class="tooltip" style="color:green">CENTER<div class="right">Calculate the center for a group of atoms, with arbitrary weights. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_e_n_t_e_r.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the group of atoms that you are calculating the Gyration Tensor for<i></i></div></div>=487,488,490,491,500 <div class="tooltip">MASS<div class="right"> calculate the center of mass<i></i></div></div>
<span style="display:none;" id="data/outside_path/plumed.2.datp5">The CENTER action with label <b>p5</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p5.value</td><td>the position of the center of mass</td></tr></table></span><b name="data/outside_path/plumed.2.datp6" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datp6","data/outside_path/plumed.2.datp6","brown")'>p6</b>: <div class="tooltip" style="color:green">CENTER<div class="right">Calculate the center for a group of atoms, with arbitrary weights. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_e_n_t_e_r.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the group of atoms that you are calculating the Gyration Tensor for<i></i></div></div>=491,492,496,497,499,500 <div class="tooltip">MASS<div class="right"> calculate the center of mass<i></i></div></div>
<br/><span style="color:blue" class="comment"># define CVs</span>
<span style="display:none;" id="data/outside_path/plumed.2.datp6">The CENTER action with label <b>p6</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p6.value</td><td>the position of the center of mass</td></tr></table></span><b name="data/outside_path/plumed.2.datdWC" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datdWC","data/outside_path/plumed.2.datdWC","brown")'>dWC</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=496,276
<span style="display:none;" id="data/outside_path/plumed.2.datdWC">The DISTANCE action with label <b>dWC</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">dWC.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/outside_path/plumed.2.datdHG" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datdHG","data/outside_path/plumed.2.datdHG","brown")'>dHG</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=490,276 
<span style="display:none;" id="data/outside_path/plumed.2.datdHG">The DISTANCE action with label <b>dHG</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">dHG.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/outside_path/plumed.2.datdHB" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datdHB","data/outside_path/plumed.2.datdHB","brown")'>dHB</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=275,493
<span style="display:none;" id="data/outside_path/plumed.2.datdHB">The DISTANCE action with label <b>dHB</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">dHB.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/outside_path/plumed.2.datdCC" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datdCC","data/outside_path/plumed.2.datdCC","brown")'>dCC</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=264,485
<span style="display:none;" id="data/outside_path/plumed.2.datdCC">The DISTANCE action with label <b>dCC</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">dCC.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/outside_path/plumed.2.datdNB" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datdNB","data/outside_path/plumed.2.datdNB","brown")'>dNB</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=<b name="data/outside_path/plumed.2.datp1_prime">p1_prime</b>,<b name="data/outside_path/plumed.2.datp2_prime">p2_prime</b>
<span style="display:none;" id="data/outside_path/plumed.2.datdNB">The DISTANCE action with label <b>dNB</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">dNB.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/outside_path/plumed.2.dattBR" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.dattBR","data/outside_path/plumed.2.dattBR","brown")'>tBR</b>: <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">VECTOR1<div class="right">two atoms that define a vector<i></i></div></div>=<b name="data/outside_path/plumed.2.datp2">p2</b>,<b name="data/outside_path/plumed.2.datp1">p1</b> <div class="tooltip">AXIS<div class="right">two atoms that define an axis<i></i></div></div>=485,487 <div class="tooltip">VECTOR2<div class="right">two atoms that define a vector<i></i></div></div>=<b name="data/outside_path/plumed.2.datp5">p5</b>,<b name="data/outside_path/plumed.2.datp6">p6</b>
<span style="display:none;" id="data/outside_path/plumed.2.dattBR">The TORSION action with label <b>tBR</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">tBR.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/outside_path/plumed.2.datcBR" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datcBR","data/outside_path/plumed.2.datcBR","brown")'>cBR</b>: <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">VECTOR1<div class="right">two atoms that define a vector<i></i></div></div>=<b name="data/outside_path/plumed.2.datp2">p2</b>,<b name="data/outside_path/plumed.2.datp1">p1</b> <div class="tooltip">AXIS<div class="right">two atoms that define an axis<i></i></div></div>=485,487 <div class="tooltip">VECTOR2<div class="right">two atoms that define a vector<i></i></div></div>=<b name="data/outside_path/plumed.2.datp5">p5</b>,<b name="data/outside_path/plumed.2.datp6">p6</b> <div class="tooltip">COSINE<div class="right"> calculate cosine instead of dihedral<i></i></div></div>
<span style="display:none;" id="data/outside_path/plumed.2.datcBR">The TORSION action with label <b>cBR</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">cBR.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/outside_path/plumed.2.datsBR" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datsBR","data/outside_path/plumed.2.datsBR","brown")'>sBR</b>: <div class="tooltip" style="color:green">CUSTOM<div class="right">Calculate a combination of variables using a custom expression. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_u_s_t_o_m.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/outside_path/plumed.2.dattBR">tBR</b> <div class="tooltip">VAR<div class="right">the names to give each of the arguments in the function<i></i></div></div>=<b name="data/outside_path/plumed.2.dattBR">tBR</b> <div class="tooltip">FUNC<div class="right">the function you wish to evaluate<i></i></div></div>=sin(tBR <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO
<span style="display:none;" id="data/outside_path/plumed.2.datsBR">The CUSTOM action with label <b>sBR</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">sBR.value</td><td>an arbitrary function</td></tr></table></span><b name="data/outside_path/plumed.2.dattBF" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.dattBF","data/outside_path/plumed.2.dattBF","brown")'>tBF</b>: <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=<b name="data/outside_path/plumed.2.datp1p2">p1p2</b>,<b name="data/outside_path/plumed.2.datp3">p3</b>,<b name="data/outside_path/plumed.2.datp4">p4</b>,<b name="data/outside_path/plumed.2.datp5">p5</b>
<br/><span style="color:blue"># --- End of included input --- </span></span><br/><span style="display:none;" id="data/outside_path/plumed.2.dattBF">The TORSION action with label <b>tBF</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">tBF.value</td><td>the TORSION involving these atoms</td></tr></table></span><div class="tooltip" style="color:green">PATHCV<div class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_a_d.html" style="color:green">More details</a><i></i></div></div> LABEL=<b name="data/outside_path/plumed.2.datpcv" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datpcv","data/outside_path/plumed.2.datpcv","brown")'>pcv</b> ARG=<b name="data/outside_path/plumed.2.datcBR">cBR</b>,<b name="data/outside_path/plumed.2.datsBR">sBR</b>,<b name="data/outside_path/plumed.2.dattBF">tBF</b> INFILE=in_cycle.input HALFLIFE=10000 PACE=500 WALKERS_RSTRIDE=500 WALKERS_ID=2 WALKERS_N=12 WALKERS_DIR=out1
<br/><b name="data/outside_path/plumed.2.datc" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datc","data/outside_path/plumed.2.datc","brown")'>c</b>: <div class="tooltip" style="color:green">CONSTANT<div class="right">Create a constant value that can be passed to actions <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_n_s_t_a_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">VALUE<div class="right">the single number that you would like to store<i></i></div></div>=-1
<span style="display:none;" id="data/outside_path/plumed.2.datc">The CONSTANT action with label <b>c</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">c.value</td><td>the constant value that was read from the plumed input</td></tr></table></span><b name="data/outside_path/plumed.2.dats" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.dats","data/outside_path/plumed.2.dats","brown")'>s</b>: <div class="tooltip" style="color:green">COMBINE<div class="right">Calculate a polynomial combination of a set of other variables. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_m_b_i_n_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=pcv.s,<b name="data/outside_path/plumed.2.datc">c</b> <div class="tooltip">COEFFICIENTS<div class="right"> the coefficients of the arguments in your function<i></i></div></div>=2.,1 <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=-1,1
<br/><span style="display:none;" id="data/outside_path/plumed.2.dats">The COMBINE action with label <b>s</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">s.value</td><td>a linear compbination</td></tr></table></span><div class="tooltip" style="color:green">UPPER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=pcv.z <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=0.0  <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=50.0 <div class="tooltip">EXP<div class="right"> the powers for the walls<i></i></div></div>=2 <div class="tooltip">EPS<div class="right"> the values for s_i in the expression for a wall<i></i></div></div>=1 <div class="tooltip">OFFSET<div class="right"> the offset for the start of the wall<i></i></div></div>=0 <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/outside_path/plumed.2.dattube" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.dattube","data/outside_path/plumed.2.dattube","brown")'>tube</b>
<br/><span style="display:none;" id="data/outside_path/plumed.2.dattube">The UPPER_WALLS action with label <b>tube</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">tube.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">tube.force2</td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span><div class="tooltip" style="color:green">METAD<div class="right">Used to performed metadynamics on one or more collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/_m_e_t_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/outside_path/plumed.2.datmetad" onclick='showPath("data/outside_path/plumed.2.dat","data/outside_path/plumed.2.datmetad","data/outside_path/plumed.2.datmetad","brown")'>metad</b> <div class="tooltip">ARG<div class="right">the labels of the scalars on which the bias will act<i></i></div></div>=<b name="data/outside_path/plumed.2.dats">s</b> <div class="tooltip">HEIGHT<div class="right">the heights of the Gaussian hills<i></i></div></div>=0.05 <div class="tooltip">SIGMA<div class="right">the widths of the Gaussian hills<i></i></div></div>=0.1 <div class="tooltip">GRID_MIN<div class="right">the lower bounds for the grid<i></i></div></div>=-1 <div class="tooltip">GRID_MAX<div class="right">the upper bounds for the grid<i></i></div></div>=1 <div class="tooltip">PACE<div class="right">the frequency for hill addition<i></i></div></div>=500 <div class="tooltip">WALKERS_RSTRIDE<div class="right">stride for reading hills files<i></i></div></div>=500 <div class="tooltip">WALKERS_ID<div class="right">walker id<i></i></div></div>=2 <div class="tooltip">WALKERS_N<div class="right">number of walkers<i></i></div></div>=9 <div class="tooltip">WALKERS_DIR<div class="right">shared directory with the hills files from all the walkers<i></i></div></div>=out1
<br/><span style="color:blue" class="comment">#FLUSH STRIDE=500</span>
<br/><span style="display:none;" id="data/outside_path/plumed.2.datmetad">The METAD action with label <b>metad</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">metad.bias</td><td>the instantaneous value of the bias potential</td></tr></table></span><div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div> <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=10 <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=out1/COLVAR
</pre>
{% endraw %}