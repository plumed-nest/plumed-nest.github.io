**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
**Source:** plumed_model_2D_WTD.dat  
**Originally used with PLUMED version:** 2.5.2  
**Stable:** [zipped raw stdout](plumed_model_2D_WTD.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_model_2D_WTD.dat.plumed.stderr.txt.zip) - [stderr](plumed_model_2D_WTD.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed_model_2D_WTD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_2D_WTD.dat.plumed_master.stderr.txt.zip) - [stderr](plumed_model_2D_WTD.dat.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/plumed_model_2D_WTD.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="plumed_model_2D_WTD.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="plumed_model_2D_WTD.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></td></tr><tr><td style="padding:1px"><img src="https://img.shields.io/badge/with-LOAD-yellow.svg" alt="tested on master" /></td></tr>
</table></div></div>
<pre style="width=97%;">
<span style="color:blue" class="comment"># LOAD FILE=PythonCV.dylib</span>
<b name="data/plumed_model_2D_WTD.datgrp" onclick='showPath("data/plumed_model_2D_WTD.dat","data/plumed_model_2D_WTD.datgrp","data/plumed_model_2D_WTD.datgrp","brown")'>grp</b>: <div class="tooltip" style="color:green">GROUP<div class="right">Define a group of atoms so that a particular list of atoms can be referenced with a single label in definitions of CVs or virtual atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_g_r_o_u_p.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the numerical indexes for the set of atoms in the group<i></i></div></div>=1-421
<span style="display:none;" id="data/plumed_model_2D_WTD.datgrp">The GROUP action with label <b>grp</b> calculates something</span><b name="data/plumed_model_2D_WTD.datcv1" onclick='showPath("data/plumed_model_2D_WTD.dat","data/plumed_model_2D_WTD.datcv1","data/plumed_model_2D_WTD.datcv1","brown")'>cv1</b>: <div class="tooltip" style="color:green">PYTHONCV<div class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_a_d.html" style="color:green">More details</a><i></i></div></div> ATOMS=1-421 IMPORT=model_2D FUNCTION=cv1 COMPONENTS=ncl,nq6
<br/><b name="data/plumed_model_2D_WTD.datcn" onclick='showPath("data/plumed_model_2D_WTD.dat","data/plumed_model_2D_WTD.datcn","data/plumed_model_2D_WTD.datcn","brown")'>cn</b>: <div class="tooltip" style="color:green">COORDINATIONNUMBER<div class="right">Calculate the coordination numbers of atoms so that you can then calculate functions of the distribution of <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">SPECIES<div class="right">this keyword is used for colvars such as coordination number<i></i></div></div>=<b name="data/plumed_model_2D_WTD.datgrp">grp</b> <div class="tooltip">SWITCH<div class="right">the switching function that it used in the construction of the contact matrix<i></i></div></div>={RATIONAL R_0=7.0 D_MAX=8.0} <div class="tooltip">LOWMEM<div class="right"> this flag does nothing and is present only to ensure back-compatibility<i></i></div></div> <div class="tooltip">MORE_THAN<div class="right">calculate the number of variables that are more than a certain target value<i></i></div></div>={RATIONAL R_0=3.0 D_MAX=13.0}
<span style="color:blue" class="comment">### calculate the number of particles with crystalline order (first shell geometries)</span>
<span style="display:none;" id="data/plumed_model_2D_WTD.datcn">The COORDINATIONNUMBER action with label <b>cn</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">cn.morethan</td><td>the number of colvars that have a value more than a threshold</td></tr><tr><td width="5%">cn.value</td><td>the coordination numbers of the specified atoms</td></tr></table></span><b name="data/plumed_model_2D_WTD.datq6" onclick='showPath("data/plumed_model_2D_WTD.dat","data/plumed_model_2D_WTD.datq6","data/plumed_model_2D_WTD.datq6","brown")'>q6</b>: <div class="tooltip" style="color:green">Q6<div class="right">Calculate sixth order Steinhardt parameters. <a href="https://www.plumed.org/doc-master/user-doc/html/_q6.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">SPECIES<div class="right">this keyword is used for colvars such as coordination number<i></i></div></div>=<b name="data/plumed_model_2D_WTD.datgrp">grp</b> <div class="tooltip">SWITCH<div class="right">the switching function that it used in the construction of the contact matrix<i></i></div></div>={RATIONAL R_0=7.0 D_MAX=8.0} <div class="tooltip">LOWMEM<div class="right"> this flag does nothing and is present only to ensure back-compatibility<i></i></div></div>
<span style="display:none;" id="data/plumed_model_2D_WTD.datq6">The Q6 action with label <b>q6</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">q6.value</td><td>the norms of the vectors of spherical harmonic coefficients</td></tr></table></span><b name="data/plumed_model_2D_WTD.datlq6" onclick='showPath("data/plumed_model_2D_WTD.dat","data/plumed_model_2D_WTD.datlq6","data/plumed_model_2D_WTD.datlq6","brown")'>lq6</b>: <div class="tooltip" style="color:green">LOCAL_Q6<div class="right">Calculate the local degree of order around an atoms by taking the average dot product between the q_6 vector on the central atom and the q_6 vector on the atoms in the first coordination sphere. <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_c_a_l__q6.html" style="color:green">More details</a><i></i></div></div> SPECIES=<b name="data/plumed_model_2D_WTD.datq6">q6</b> <div class="tooltip">SWITCH<div class="right">This keyword is used if you want to employ an alternative to the continuous swiching function defined above<i></i></div></div>={RATIONAL R_0=7.0 D_MAX=8.0} <div class="tooltip">LOWMEM<div class="right"> this flag does nothing and is present only to ensure back-compatibility<i></i></div></div>
<span style="display:none;" id="data/plumed_model_2D_WTD.datlq6">The LOCAL_Q6 action with label <b>lq6</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">lq6.value</td><td>the values of the local steinhardt parameters for the input atoms</td></tr></table></span><b name="data/plumed_model_2D_WTD.datflq6" onclick='showPath("data/plumed_model_2D_WTD.dat","data/plumed_model_2D_WTD.datflq6","data/plumed_model_2D_WTD.datflq6","brown")'>flq6</b>: <div class="tooltip" style="color:green">MFILTER_MORE<div class="right">Basically equivalent to MORE_THAN. <a href="https://www.plumed.org/doc-master/user-doc/html/_m_f_i_l_t_e_r__m_o_r_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">DATA<div class="right">the vector you wish to transform<i></i></div></div>=<b name="data/plumed_model_2D_WTD.datlq6">lq6</b> <div class="tooltip">SWITCH<div class="right">the switching function that transform<i></i></div></div>={GAUSSIAN R_0=0.69 D_MAX=0.70}
<br/><span style="color:blue" class="comment">### calculate the coordination number distributions for these crystalline particles and count them</span>
<span style="display:none;" id="data/plumed_model_2D_WTD.datflq6">The MFILTER_MORE action with label <b>flq6</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr></table></span><b name="data/plumed_model_2D_WTD.datcnq6" onclick='showPath("data/plumed_model_2D_WTD.dat","data/plumed_model_2D_WTD.datcnq6","data/plumed_model_2D_WTD.datcnq6","brown")'>cnq6</b>: <div class="tooltip" style="color:green">COORDINATIONNUMBER<div class="right">Calculate the coordination numbers of atoms so that you can then calculate functions of the distribution of <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">SPECIES<div class="right">this keyword is used for colvars such as coordination number<i></i></div></div>=<b name="data/plumed_model_2D_WTD.datflq6">flq6</b> <div class="tooltip">SWITCH<div class="right">the switching function that it used in the construction of the contact matrix<i></i></div></div>={RATIONAL R_0=7.0 D_MAX=8.0} <div class="tooltip">MEAN<div class="right"> calculate the mean of all the quantities<i></i></div></div> <div class="tooltip">MORE_THAN<div class="right">calculate the number of variables that are more than a certain target value<i></i></div></div>={RATIONAL R_0=11.0 D_MAX=13.0}
<br/><span style="display:none;" id="data/plumed_model_2D_WTD.datcnq6">The COORDINATIONNUMBER action with label <b>cnq6</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">cnq6.morethan</td><td>the number of colvars that have a value more than a threshold</td></tr><tr><td width="5%">cnq6.mean</td><td>the mean of the colvars</td></tr><tr><td width="5%">cnq6.value</td><td>the coordination numbers of the specified atoms</td></tr></table></span><b name="data/plumed_model_2D_WTD.datn" onclick='showPath("data/plumed_model_2D_WTD.dat","data/plumed_model_2D_WTD.datn","data/plumed_model_2D_WTD.datn","brown")'>n</b>: <div class="tooltip" style="color:green">COMBINE<div class="right">Calculate a polynomial combination of a set of other variables. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_m_b_i_n_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/plumed_model_2D_WTD.datcn">cn.morethan</b> <div class="tooltip">POWERS<div class="right"> the powers to which you are raising each of the arguments in your function<i></i></div></div>=0.33333333 <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO
<span style="display:none;" id="data/plumed_model_2D_WTD.datn">The COMBINE action with label <b>n</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">n.value</td><td>a linear compbination</td></tr></table></span><b name="data/plumed_model_2D_WTD.datnq6" onclick='showPath("data/plumed_model_2D_WTD.dat","data/plumed_model_2D_WTD.datnq6","data/plumed_model_2D_WTD.datnq6","brown")'>nq6</b>: <div class="tooltip" style="color:green">COMBINE<div class="right">Calculate a polynomial combination of a set of other variables. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_m_b_i_n_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/plumed_model_2D_WTD.datcnq6">cnq6.morethan</b> <div class="tooltip">POWERS<div class="right"> the powers to which you are raising each of the arguments in your function<i></i></div></div>=0.333333 <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO
<br/><span style="display:none;" id="data/plumed_model_2D_WTD.datnq6">The COMBINE action with label <b>nq6</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">nq6.value</td><td>a linear compbination</td></tr></table></span><b name="data/plumed_model_2D_WTD.datlwall" onclick='showPath("data/plumed_model_2D_WTD.dat","data/plumed_model_2D_WTD.datlwall","data/plumed_model_2D_WTD.datlwall","brown")'>lwall</b>: <div class="tooltip" style="color:green">LOWER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=cv1.nq6 <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=-0.5 <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=150.0 <div class="tooltip">EXP<div class="right"> the powers for the walls<i></i></div></div>=4 <div class="tooltip">EPS<div class="right"> the values for s_i in the expression for a wall<i></i></div></div>=1 <div class="tooltip">OFFSET<div class="right"> the offset for the start of the wall<i></i></div></div>=0
<br/><span style="display:none;" id="data/plumed_model_2D_WTD.datlwall">The LOWER_WALLS action with label <b>lwall</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">lwall.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">lwall.force2</td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span><b name="data/plumed_model_2D_WTD.datres" onclick='showPath("data/plumed_model_2D_WTD.dat","data/plumed_model_2D_WTD.datres","data/plumed_model_2D_WTD.datres","brown")'>res</b>: <div class="tooltip" style="color:green">METAD<div class="right">Used to performed metadynamics on one or more collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/_m_e_t_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the scalars on which the bias will act<i></i></div></div>=cv1.ncl,cv1.nq6 <div class="tooltip">SIGMA<div class="right">the widths of the Gaussian hills<i></i></div></div>=0.18,0.05 <div class="tooltip">HEIGHT<div class="right">the heights of the Gaussian hills<i></i></div></div>=0.1 <div class="tooltip">PACE<div class="right">the frequency for hill addition<i></i></div></div>=1000 <div class="tooltip">BIASFACTOR<div class="right">use well tempered metadynamics and use this bias factor<i></i></div></div>=50 <div class="tooltip">TEMP<div class="right">the system temperature - this is only needed if you are doing well-tempered metadynamics<i></i></div></div>=2 <div class="tooltip">GRID_MIN<div class="right">the lower bounds for the grid<i></i></div></div>=-0.5,-1.5 <div class="tooltip">GRID_MAX<div class="right">the upper bounds for the grid<i></i></div></div>=10,8 <div class="tooltip">GRID_BIN<div class="right">the number of bins for the grid<i></i></div></div>=200,200
<br/><span style="display:none;" id="data/plumed_model_2D_WTD.datres">The METAD action with label <b>res</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">res.bias</td><td>the instantaneous value of the bias potential</td></tr></table></span><div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=colvar.out <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=cv1.ncl,cv1.nq6,<b name="data/plumed_model_2D_WTD.datres">res.bias</b>,<b name="data/plumed_model_2D_WTD.datres">res.work</b>,<b name="data/plumed_model_2D_WTD.datcn">cn.morethan</b>,<b name="data/plumed_model_2D_WTD.datcnq6">cnq6.morethan</b> <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=500
</pre>
{% endraw %}