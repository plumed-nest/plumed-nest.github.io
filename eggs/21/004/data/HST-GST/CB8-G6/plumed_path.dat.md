**Project ID:** [plumID:21.004]({{ '/' | absolute_url }}eggs/21/004/)  
**Source:** HST-GST/CB8-G6/plumed_path.dat  
**Originally used with PLUMED version:** 2.5  
**Stable:** [zipped raw stdout](plumed_path.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_path.dat.plumed.stderr.txt.zip) - [stderr](plumed_path.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed_path.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_path.dat.plumed_master.stderr.txt.zip) - [stderr](plumed_path.dat.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/HST-GST/CB8-G6/plumed_path.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="plumed_path.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="plumed_path.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></td></tr></table></div></div>
<pre style="width=97%;">
<span style="color:blue" class="comment">#</span>
<div class="tooltip" style="color:green">RESTART<div class="right">Activate restart. <a href="https://www.plumed.org/doc-master/user-doc/html/_r_e_s_t_a_r_t.html" style="color:green">More details</a><i></i></div></div>
<br/><span style="display:none;" id="data/HST-GST/CB8-G6/plumed_path.dat">The RESTART action with label <b></b> calculates something</span><div class="tooltip" style="color:green">WHOLEMOLECULES<div class="right">This action is used to rebuild molecules that can become split by the periodic boundary conditions. <a href="https://www.plumed.org/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ENTITY0<div class="right">the atoms that make up a molecule that you wish to align<i></i></div></div>=1-168 <div class="tooltip">STRIDE<div class="right"> the frequency with which molecules are reassembled<i></i></div></div>=1
<b name="data/HST-GST/CB8-G6/plumed_path.datp" onclick='showPath("data/HST-GST/CB8-G6/plumed_path.dat","data/HST-GST/CB8-G6/plumed_path.datp","data/HST-GST/CB8-G6/plumed_path.datp","black")'>p</b><span style="display:none;" id="data/HST-GST/CB8-G6/plumed_path.datp">The PATHMSD action with label <b>p</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p.sss</td><td width="5%"><font color="black">scalar</font></td><td>the position on the path</td></tr><tr><td width="5%">p.zzz</td><td width="5%"><font color="black">scalar</font></td><td>the distance from the path</td></tr></table></span>: <div class="tooltip" style="color:green">PATHMSD<div class="right">This Colvar calculates path collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_a_t_h_m_s_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">REFERENCE<div class="right">the pdb is needed to provide the various milestones<i></i></div></div>=path.pdb  <div class="tooltip">LAMBDA<div class="right">the lambda parameter is needed for smoothing, is in the units of plumed<i></i></div></div>=230.0 <div class="tooltip">NEIGH_STRIDE<div class="right">how often the neighbor list needs to be calculated in time units<i></i></div></div>=4 <div class="tooltip">NEIGH_SIZE<div class="right">size of the neighbor list<i></i></div></div>=8
<br/><span id="data/HST-GST/CB8-G6/plumed_path.datdefmeta_short"><b name="data/HST-GST/CB8-G6/plumed_path.datmeta" onclick='showPath("data/HST-GST/CB8-G6/plumed_path.dat","data/HST-GST/CB8-G6/plumed_path.datmeta","data/HST-GST/CB8-G6/plumed_path.datmeta","black")'>meta</b><span style="display:none;" id="data/HST-GST/CB8-G6/plumed_path.datmeta">The METAD action with label <b>meta</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">meta.bias</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the bias potential</td></tr></table></span>: <div class="tooltip" style="color:green">METAD<div class="right">Used to performed metadynamics on one or more collective variables. This action has <a class="toggler" href='javascript:;' onclick='toggleDisplay("data/HST-GST/CB8-G6/plumed_path.datdefmeta");'>hidden defaults</a>. <a href="https://www.plumed.org/doc-master/user-doc/html/_m_e_t_a_d.html">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the scalars on which the bias will act<i></i></div></div>=<b name="data/HST-GST/CB8-G6/plumed_path.datp">p.sss</b>,<b name="data/HST-GST/CB8-G6/plumed_path.datp">p.zzz</b> <div class="tooltip">SIGMA<div class="right">the widths of the Gaussian hills<i></i></div></div>=0.2,0.01 <div class="tooltip">HEIGHT<div class="right">the heights of the Gaussian hills<i></i></div></div>=0.84 <div class="tooltip">TEMP<div class="right">the system temperature - this is only needed if you are doing well-tempered metadynamics<i></i></div></div>=300 <div class="tooltip">BIASFACTOR<div class="right">use well tempered metadynamics and use this bias factor<i></i></div></div>=15 <div class="tooltip">PACE<div class="right">the frequency for hill addition<i></i></div></div>=500 <div class="tooltip">GRID_MIN<div class="right">the lower bounds for the grid<i></i></div></div>=1,-0.015 <div class="tooltip">GRID_MAX<div class="right">the upper bounds for the grid<i></i></div></div>=55,0.19
</span><span id="data/HST-GST/CB8-G6/plumed_path.datdefmeta_long" style="display:none;"><b name="data/HST-GST/CB8-G6/plumed_path.datmeta" onclick='showPath("data/HST-GST/CB8-G6/plumed_path.dat","data/HST-GST/CB8-G6/plumed_path.datmeta","data/HST-GST/CB8-G6/plumed_path.datmeta","black")'>meta</b>: <div class="tooltip" style="color:green">METAD<div class="right">Used to performed metadynamics on one or more collective variables. This action uses the <a class="toggler" href='javascript:;' onclick='toggleDisplay("data/HST-GST/CB8-G6/plumed_path.datdefmeta");'>defaults shown here</a>. <a href="https://www.plumed.org/doc-master/user-doc/html/_m_e_t_a_d.html">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the scalars on which the bias will act<i></i></div></div>=<b name="data/HST-GST/CB8-G6/plumed_path.datp">p.sss</b>,<b name="data/HST-GST/CB8-G6/plumed_path.datp">p.zzz</b> <div class="tooltip">SIGMA<div class="right">the widths of the Gaussian hills<i></i></div></div>=0.2,0.01 <div class="tooltip">HEIGHT<div class="right">the heights of the Gaussian hills<i></i></div></div>=0.84 <div class="tooltip">TEMP<div class="right">the system temperature - this is only needed if you are doing well-tempered metadynamics<i></i></div></div>=300 <div class="tooltip">BIASFACTOR<div class="right">use well tempered metadynamics and use this bias factor<i></i></div></div>=15 <div class="tooltip">PACE<div class="right">the frequency for hill addition<i></i></div></div>=500 <div class="tooltip">GRID_MIN<div class="right">the lower bounds for the grid<i></i></div></div>=1,-0.015 <div class="tooltip">GRID_MAX<div class="right">the upper bounds for the grid<i></i></div></div>=55,0.19  <div class="tooltip">FILE<div class="right"> a file in which the list of added hills is stored<i></i></div></div>=HILLS
</span><b name="data/HST-GST/CB8-G6/plumed_path.datuwall_z" onclick='showPath("data/HST-GST/CB8-G6/plumed_path.dat","data/HST-GST/CB8-G6/plumed_path.datuwall_z","data/HST-GST/CB8-G6/plumed_path.datuwall_z","black")'>uwall_z</b><span style="display:none;" id="data/HST-GST/CB8-G6/plumed_path.datuwall_z">The UPPER_WALLS action with label <b>uwall_z</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">uwall_z.bias</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">uwall_z.force2</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span>: <div class="tooltip" style="color:green">UPPER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=<b name="data/HST-GST/CB8-G6/plumed_path.datp">p.zzz</b> <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=0.05 <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=40000000.0
<b name="data/HST-GST/CB8-G6/plumed_path.datlwall_s_o" onclick='showPath("data/HST-GST/CB8-G6/plumed_path.dat","data/HST-GST/CB8-G6/plumed_path.datlwall_s_o","data/HST-GST/CB8-G6/plumed_path.datlwall_s_o","black")'>lwall_s_o</b><span style="display:none;" id="data/HST-GST/CB8-G6/plumed_path.datlwall_s_o">The LOWER_WALLS action with label <b>lwall_s_o</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">lwall_s_o.bias</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">lwall_s_o.force2</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span>: <div class="tooltip" style="color:green">LOWER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=<b name="data/HST-GST/CB8-G6/plumed_path.datp">p.sss</b> <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=1  <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=20000.0
<b name="data/HST-GST/CB8-G6/plumed_path.datuwall_s_i" onclick='showPath("data/HST-GST/CB8-G6/plumed_path.dat","data/HST-GST/CB8-G6/plumed_path.datuwall_s_i","data/HST-GST/CB8-G6/plumed_path.datuwall_s_i","black")'>uwall_s_i</b><span style="display:none;" id="data/HST-GST/CB8-G6/plumed_path.datuwall_s_i">The UPPER_WALLS action with label <b>uwall_s_i</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">uwall_s_i.bias</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">uwall_s_i.force2</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span>: <div class="tooltip" style="color:green">UPPER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=<b name="data/HST-GST/CB8-G6/plumed_path.datp">p.sss</b> <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=55 <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=20000.0
<br/><div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=<b name="data/HST-GST/CB8-G6/plumed_path.datp">p.sss</b>,<b name="data/HST-GST/CB8-G6/plumed_path.datp">p.zzz</b> <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=250 <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=COLV_Path <div class="tooltip">FMT<div class="right">the format that should be used to output real numbers<i></i></div></div>=%8.4f
</pre>
{% endraw %}