**Project ID:** [plumID:21.036]({{ '/' | absolute_url }}eggs/21/036/)  
**Source:** DHH1N_sampling/BEMD/CV5/plumed.4.dat  
**Originally used with PLUMED version:** 2.5.2  
**Stable:** [zipped raw stdout](plumed.4.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.4.dat.plumed.stderr.txt.zip) - [stderr](plumed.4.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.4.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.4.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.4.dat.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/DHH1N_sampling/BEMD/CV5/plumed.4.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="plumed.4.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="plumed.4.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></td></tr></table></div></div>
<pre style="width=97%;">
<span style="color:blue" class="comment">#RESTART</span>
<br/><div class="tooltip" style="color:green">MOLINFO<div class="right">This command is used to provide information on the molecules that are present in your system. <a href="https://www.plumed.org/doc-master/user-doc/html/_m_o_l_i_n_f_o.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">STRUCTURE<div class="right">a file in pdb format containing a reference structure<i></i></div></div>=Protein.pdb <div class="tooltip">MOLTYPE<div class="right"> what kind of molecule is contained in the pdb file - usually not needed since protein/RNA/DNA are compatible<i></i></div></div>=protein
<br/><span style="display:none;" id="data/DHH1N_sampling/BEMD/CV5/plumed.4.dat">The MOLINFO action with label <b></b> calculates something</span><div class="tooltip" style="color:green">WHOLEMOLECULES<div class="right">This action is used to rebuild molecules that can become split by the periodic boundary conditions. <a href="https://www.plumed.org/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ENTITY0<div class="right">the atoms that make up a molecule that you wish to align<i></i></div></div>=1-709
<br/><div class="tooltip" style="color:green">RANDOM_EXCHANGES<div class="right">Set random pattern for exchanges. <a href="https://www.plumed.org/doc-master/user-doc/html/_r_a_n_d_o_m__e_x_c_h_a_n_g_e_s.html" style="color:green">More details</a><i></i></div></div>
<br/><span id="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_short"><span id="data/DHH1N_sampling/BEMD/CV5/plumed.4.datdefcv5_short"><b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5" onclick='showPath("data/DHH1N_sampling/BEMD/CV5/plumed.4.dat","data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5","data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_shortcut","black")'>cv5</b><span style="display:none;" id="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_shortcut">The ALPHARMSD action with label <b>cv5</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">cv5</td><td width="5%"><font color="black">scalar</font></td><td>if LESS_THAN is present the RMSD distance between each residue and the ideal alpha helix.  If LESS_THAN is not present the number of residue segments where the structure is similar to an alpha helix</td></tr></table></span>: <div class="tooltip" style="color:green">ALPHARMSD<div class="right">Probe the alpha helical content of a protein structure. This action is <a class="toggler" href='javascript:;' onclick='toggleDisplay("data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5");'>a shortcut</a> and it has <a class="toggler" href='javascript:;' onclick='toggleDisplay("data/DHH1N_sampling/BEMD/CV5/plumed.4.datdefcv5");'>hidden defaults</a>. <a href="https://www.plumed.org/doc-master/user-doc/html/_a_l_p_h_a_r_m_s_d.html">More details</a><i></i></div></div> <div class="tooltip">RESIDUES<div class="right">this command is used to specify the set of residues that could conceivably form part of the secondary structure<i></i></div></div>=1-45 <div class="tooltip">TYPE<div class="right"> the manner in which RMSD alignment is performed<i></i></div></div>=DRMSD <div class="tooltip">R_0<div class="right">The r_0 parameter of the switching function<i></i></div></div>=0.08 <div class="tooltip">NN<div class="right"> The n parameter of the switching function<i></i></div></div>=2 <div class="tooltip">MM<div class="right"> The m parameter of the switching function<i></i></div></div>=4 <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions<i></i></div></div>
</span><span id="data/DHH1N_sampling/BEMD/CV5/plumed.4.datdefcv5_long" style="display:none;"><b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5" onclick='showPath("data/DHH1N_sampling/BEMD/CV5/plumed.4.dat","data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5","data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_shortcut","black")'>cv5</b>: <div class="tooltip" style="color:green">ALPHARMSD<div class="right">Probe the alpha helical content of a protein structure. This action is <a class="toggler" href='javascript:;' onclick='toggleDisplay("data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5");'>a shortcut</a> and uses the <a class="toggler" href='javascript:;' onclick='toggleDisplay("data/DHH1N_sampling/BEMD/CV5/plumed.4.datdefcv5");'>defaults shown here</a>. <a href="https://www.plumed.org/doc-master/user-doc/html/_a_l_p_h_a_r_m_s_d.html">More details</a><i></i></div></div> <div class="tooltip">RESIDUES<div class="right">this command is used to specify the set of residues that could conceivably form part of the secondary structure<i></i></div></div>=1-45 <div class="tooltip">TYPE<div class="right"> the manner in which RMSD alignment is performed<i></i></div></div>=DRMSD <div class="tooltip">R_0<div class="right">The r_0 parameter of the switching function<i></i></div></div>=0.08 <div class="tooltip">NN<div class="right"> The n parameter of the switching function<i></i></div></div>=2 <div class="tooltip">MM<div class="right"> The m parameter of the switching function<i></i></div></div>=4 <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions<i></i></div></div>  <div class="tooltip">D_0<div class="right"> The d_0 parameter of the switching function<i></i></div></div>=0.0
</span></span><span id="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_long" style="display:none;"><span style="color:blue" class="comment"># PLUMED interprets the command:
</span><span class="toggler" style="color:red" onclick='toggleDisplay("data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5")'># cv5: ALPHARMSD RESIDUES=1-45 TYPE=DRMSD R_0=0.08 NN=2 MM=4 NOPBC</span>
<span style="color:blue" class="comment"># as follows (Click the red comment above to revert to the short version of the input):</span>
<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_rmsd" onclick='showPath("data/DHH1N_sampling/BEMD/CV5/plumed.4.dat","data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_rmsd","data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_rmsd","blue")'>cv5_rmsd</b><span style="display:none;" id="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_rmsd">The SECONDARY_STRUCTURE_RMSD action with label <b>cv5_rmsd</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">cv5_rmsd</td><td width="5%"><font color="blue">vector</font></td><td>a vector containing the rmsd distance between each of the residue segments and the reference structure</td></tr></table></span>: <div class="tooltip" style="color:green">SECONDARY_STRUCTURE_RMSD<div class="right">Calclulate the distance between segments of a protein and a reference structure of interest <a href="https://www.plumed.org/doc-master/user-doc/html/_s_e_c_o_n_d_a_r_y__s_t_r_u_c_t_u_r_e__r_m_s_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">BONDLENGTH<div class="right">the length to use for bonds<i></i></div></div>=0.17 <div class="tooltip">ATOMS<div class="right">this is the full list of atoms that we are investigating<i></i></div></div>=1,5,7,8,9,10,12,14,19,20,21,23,25,38,39,40,42,44,52,53,54,56,58,66,67,68,70,72,80,81,82,84,86,100,101,102,104,106,114,115,116,118,120,128,129,130,132,134,142,143,144,146,148,156,157,158,160,162,170,171,172,174,176,181,182,183,185,187,195,196,197,199,201,209,210,211,213,215,221,222,223,225,227,240,241,242,244,246,252,253,254,256,258,276,277,278,280,282,288,289,290,292,294,312,313,314,316,318,334,335,336,338,340,348,349,350,352,354,358,359,360,362,364,377,378,379,381,383,391,392,393,395,397,410,411,412,416,418,424,425,426,428,430,446,447,448,450,452,468,469,470,472,474,480,481,482,484,486,494,495,496,498,500,518,519,520,524,526,532,533,534,536,538,549,550,551,553,555,563,564,565,567,569,575,576,577,579,581,587,588,589,591,593,603,604,605,607,609,622,623,624,626,628,636,637,638,640,642,650,651,652,654,656,672,673,674,676,678,679,680,681,683,685,693,694 <div class="tooltip">TYPE<div class="right"> the manner in which RMSD alignment is performed<i></i></div></div>=DRMSD <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions<i></i></div></div> <div class="tooltip">SEGMENT1<div class="right">this is the lists of atoms in the segment that are being considered<i></i></div></div>=0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29 <div class="tooltip">SEGMENT2<div class="right">this is the lists of atoms in the segment that are being considered<i></i></div></div>=5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34 <div class="tooltip">SEGMENT3<div class="right">this is the lists of atoms in the segment that are being considered<i></i></div></div>=10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39 <div class="tooltip">SEGMENT4<div class="right">this is the lists of atoms in the segment that are being considered<i></i></div></div>=15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44 <div class="tooltip">SEGMENT5<div class="right">this is the lists of atoms in the segment that are being considered<i></i></div></div>=20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49 <div class="tooltip">STRUCTURE1<div class="right">the reference structure<i></i></div></div>=0.733,0.519,5.298,1.763,0.81,4.301,3.166,0.543,4.881,1.527,-0.045,3.053,1.646,0.436,1.928,1.18,-1.312,3.254,0.924,-2.203,2.126,0.65,-3.626,2.626,-0.239,-1.711,1.261,-0.19,-1.815,0.032,-1.28,-1.172,1.891,-2.416,-0.661,1.127,-3.548,-0.217,2.056,-1.964,0.529,0.276,-2.364,0.659,-0.88,-1.13,1.391,0.856,-0.62,2.565,0.148,0.228,3.439,1.077,0.231,2.129,-1.032,0.179,2.733,-2.099,1.028,1.084,-0.833,1.872,0.593,-1.919,2.85,-0.462,-1.397,1.02,0.02,-3.049,1.317,0.227,-4.224,-0.051,-0.684,-2.696,-0.927,-1.261,-3.713,-1.933,-2.219,-3.074,-1.663,-0.171,-4.475,-1.916,-0.296,-5.673     <span style="color:blue" class="comment"># Action input conctinues with 35 further SEGMENTn keywords, </span>
<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_lt" onclick='showPath("data/DHH1N_sampling/BEMD/CV5/plumed.4.dat","data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_lt","data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_lt","blue")'>cv5_lt</b><span style="display:none;" id="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_lt">The LESS_THAN action with label <b>cv5_lt</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">cv5_lt</td><td width="5%"><font color="blue">vector</font></td><td>the vector obtained by doing an element-wise application of a function that is one if the input is less than a threshold to the input vectors</td></tr></table></span>: <div class="tooltip" style="color:green">LESS_THAN<div class="right">Use a switching function to determine how many of the input variables are less than a certain cutoff. <a href="https://www.plumed.org/doc-master/user-doc/html/_l_e_s_s__t_h_a_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_rmsd">cv5_rmsd</b> <div class="tooltip">SWITCH<div class="right">This keyword is used if you want to employ an alternative to the continuous swiching function defined above<i></i></div></div>={RATIONAL R_0=0.08 D_0=0.0 NN=2 MM=4}
<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5" onclick='showPath("data/DHH1N_sampling/BEMD/CV5/plumed.4.dat","data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5","data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5","black")'>cv5</b><span style="display:none;" id="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5">The SUM action with label <b>cv5</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">cv5</td><td width="5%"><font color="black">scalar</font></td><td>the sum of all the elements in the input vector</td></tr></table></span>: <div class="tooltip" style="color:green">SUM<div class="right">Calculate the sum of the arguments <a href="https://www.plumed.org/doc-master/user-doc/html/_s_u_m.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5_lt">cv5_lt</b> <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO
<span style="color:blue"># --- End of included input --- </span></span><br/><b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datlwall" onclick='showPath("data/DHH1N_sampling/BEMD/CV5/plumed.4.dat","data/DHH1N_sampling/BEMD/CV5/plumed.4.datlwall","data/DHH1N_sampling/BEMD/CV5/plumed.4.datlwall","black")'>lwall</b><span style="display:none;" id="data/DHH1N_sampling/BEMD/CV5/plumed.4.datlwall">The LOWER_WALLS action with label <b>lwall</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">lwall.bias</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">lwall.force2</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span>: <div class="tooltip" style="color:green">LOWER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5">cv5</b> <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=2.0 <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=30.0
<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datuwall" onclick='showPath("data/DHH1N_sampling/BEMD/CV5/plumed.4.dat","data/DHH1N_sampling/BEMD/CV5/plumed.4.datuwall","data/DHH1N_sampling/BEMD/CV5/plumed.4.datuwall","black")'>uwall</b><span style="display:none;" id="data/DHH1N_sampling/BEMD/CV5/plumed.4.datuwall">The UPPER_WALLS action with label <b>uwall</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">uwall.bias</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">uwall.force2</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span>: <div class="tooltip" style="color:green">UPPER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5">cv5</b> <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=15.0 <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=30.0
<br/><b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datmetad" onclick='showPath("data/DHH1N_sampling/BEMD/CV5/plumed.4.dat","data/DHH1N_sampling/BEMD/CV5/plumed.4.datmetad","data/DHH1N_sampling/BEMD/CV5/plumed.4.datmetad","black")'>metad</b><span style="display:none;" id="data/DHH1N_sampling/BEMD/CV5/plumed.4.datmetad">The METAD action with label <b>metad</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">metad.bias</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the bias potential</td></tr></table></span>: <div class="tooltip" style="color:green">METAD<div class="right">Used to performed metadynamics on one or more collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/_m_e_t_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the scalars on which the bias will act<i></i></div></div>=<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5">cv5</b> <div class="tooltip">PACE<div class="right">the frequency for hill addition<i></i></div></div>=2500 <div class="tooltip">HEIGHT<div class="right">the heights of the Gaussian hills<i></i></div></div>=0.3 <div class="tooltip">SIGMA<div class="right">the widths of the Gaussian hills<i></i></div></div>=0.1 <div class="tooltip">FILE<div class="right"> a file in which the list of added hills is stored<i></i></div></div>=HILLS <div class="tooltip">GRID_MIN<div class="right">the lower bounds for the grid<i></i></div></div>=0.0 <div class="tooltip">GRID_MAX<div class="right">the upper bounds for the grid<i></i></div></div>=30.0 <div class="tooltip">GRID_SPACING<div class="right">the approximate grid spacing (to be used as an alternative or together with GRID_BIN)<i></i></div></div>=0.025
<br/><div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=10 <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datcv5">cv5</b>,<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datmetad">metad.bias</b>,<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datuwall">uwall.bias</b>,<b name="data/DHH1N_sampling/BEMD/CV5/plumed.4.datlwall">lwall.bias</b> <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=COLVAR
<span style="color:blue" class="comment">#PRINT STRIDE=10 ARG=cv5,metad.bias FILE=COLVAR</span>
</pre>
{% endraw %}