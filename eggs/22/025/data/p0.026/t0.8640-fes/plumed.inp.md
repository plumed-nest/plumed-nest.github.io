**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
**Source:** p0.026/t0.8640-fes/plumed.inp  
**Originally used with PLUMED version:** 2.8  
**Stable:** [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) - [stderr](plumed.inp.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) - [stderr](plumed.inp.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/p0.026/t0.8640-fes/plumed.inp"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="plumed.inp.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="plumed.inp.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></td></tr><tr><td style="padding:1px"><img src="https://img.shields.io/badge/with-LOAD-yellow.svg" alt="tested on master" /></td></tr>
</table></div></div>
<pre style="width=97%;">
<div class="tooltip" style="color:green">LOAD<div class="right">Loads a library, possibly defining new actions. <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">FILE<div class="right">file to be loaded<i></i></div></div>=../../code/ReweightGeomFES.cpp
 
<span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inp">The LOAD action with label <b></b> calculates something</span><div class="tooltip" style="color:green">UNITS<div class="right">This command sets the internal units for the code. <a href="https://www.plumed.org/doc-master/user-doc/html/_u_n_i_t_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">NATURAL<div class="right"> use natural units<i></i></div></div>
<br/><div class="tooltip" style="color:green">VOLUME<div class="right">Calculate the volume of the simulation box. <a href="https://www.plumed.org/doc-master/user-doc/html/_v_o_l_u_m_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpvol" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpvol","data/p0.026/t0.8640-fes/plumed.inpvol","brown")'>vol</b>
<span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpvol">The VOLUME action with label <b>vol</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">vol.value</td><td>the volume of simulation box</td></tr></table></span><div class="tooltip" style="color:green">CUSTOM<div class="right">Calculate a combination of variables using a custom expression. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_u_s_t_o_m.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpvol">vol</b> <div class="tooltip">FUNC<div class="right">the function you wish to evaluate<i></i></div></div>=x/17576 <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpmolvol" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpmolvol","data/p0.026/t0.8640-fes/plumed.inpmolvol","brown")'>molvol</b>
<br/><span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpmolvol">The CUSTOM action with label <b>molvol</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">molvol.value</td><td>an arbitrary function</td></tr></table></span><div class="tooltip" style="color:green">COORDINATIONNUMBER<div class="right">Calculate the coordination numbers of atoms so that you can then calculate functions of the distribution of <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html" style="color:green">More details</a><i></i></div></div> ...
  <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpcoord" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpcoord","data/p0.026/t0.8640-fes/plumed.inpcoord","brown")'>coord</b>
  <div class="tooltip">SPECIES<div class="right">this keyword is used for colvars such as coordination number<i></i></div></div>=1-17576
  <div class="tooltip">SWITCH<div class="right">the switching function that it used in the construction of the contact matrix<i></i></div></div>={RATIONAL R_0=1.6 D_MAX=2.5}
  <div class="tooltip">LESS_THAN<div class="right">calculate the number of variables that are less than a certain target value<i></i></div></div>={RATIONAL R_0=5 D_MAX=7.5 NN=12}
  <div class="tooltip">LOWMEM<div class="right"> this flag does nothing and is present only to ensure back-compatibility<i></i></div></div>
... COORDINATIONNUMBER
<br/><span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpcoord">The COORDINATIONNUMBER action with label <b>coord</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">coord.lessthan</td><td>the number of colvars that have a value less than a threshold</td></tr><tr><td width="5%">coord.value</td><td>the coordination numbers of the specified atoms</td></tr></table></span><div class="tooltip" style="color:green">UPPER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpmolvol">molvol</b> <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=2.0 <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=1e5 <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpwall1" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpwall1","data/p0.026/t0.8640-fes/plumed.inpwall1","brown")'>wall1</b>
<span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpwall1">The UPPER_WALLS action with label <b>wall1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">wall1.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">wall1.force2</td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span><div class="tooltip" style="color:green">UPPER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpcoord">coord.lessthan</b> <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=1e5 <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=1.0 <div class="tooltip">STRIDE<div class="right">the frequency with which the forces due to the bias should be calculated<i></i></div></div>=200 <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpwall2" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpwall2","data/p0.026/t0.8640-fes/plumed.inpwall2","brown")'>wall2</b>
<br/><span style="color:blue" class="comment"># ANN BIAS</span>
<span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpwall2">The UPPER_WALLS action with label <b>wall2</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">wall2.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">wall2.force2</td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span><div class="tooltip" style="color:green">ANN<div class="right">Calculates the ANN-function. <a href="https://www.plumed.org/doc-master/user-doc/html/_a_n_n.html" style="color:green">More details</a><i></i></div></div> ...
  <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpfesfit" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpfesfit","data/p0.026/t0.8640-fes/plumed.inpfesfit","brown")'>fesfit</b>
  <div class="tooltip">ARG<div class="right">the labels of the values from which the function is calculated<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpmolvol">molvol</b>
  <div class="tooltip">NUM_LAYERS<div class="right">number of layers of the neural network<i></i></div></div>=4
  <div class="tooltip">NUM_NODES<div class="right">numbers of nodes in each layer of the neural network<i></i></div></div>=1,1,12,1
  <div class="tooltip">ACTIVATIONS<div class="right">activation functions for the neural network<i></i></div></div>=Linear,Tanh,Linear
  <div class="tooltip">WEIGHTS0<div class="right">flattened weight arrays connecting adjacent layers, WEIGHTS0 represents flattened weight array connecting layer 0 and layer 1, WEIGHTS1 represents flattened weight array connecting layer 1 and layer 2, <i></i></div></div>=10.0
  <div class="tooltip">WEIGHTS1<div class="right">flattened weight arrays connecting adjacent layers, WEIGHTS0 represents flattened weight array connecting layer 0 and layer 1, WEIGHTS1 represents flattened weight array connecting layer 1 and layer 2, <i></i></div></div>=2.16563713,0.42761304,2.95540812,-2.41171897,0.45126841,-0.4149445,1.88089253,-0.42054699,-0.4136319,0.40413625,0.43153124,0.40268593
  <div class="tooltip">WEIGHTS2<div class="right">flattened weight arrays connecting adjacent layers, WEIGHTS0 represents flattened weight array connecting layer 0 and layer 1, WEIGHTS1 represents flattened weight array connecting layer 1 and layer 2, <i></i></div></div>=-4.81832049,-1.06672746,2.99806168,-1.35381046,-1.02319136,1.1083244,-3.01007281,1.36477388,1.17316488,-1.78819964,-1.09795806,-1.47446224
  <div class="tooltip">BIASES0<div class="right">bias array for each layer of the neural network, BIASES0 represents bias array for layer 1, BIASES1 represents bias array for layer 2, <i></i></div></div>=-18.0
  <div class="tooltip">BIASES1<div class="right">bias array for each layer of the neural network, BIASES0 represents bias array for layer 1, BIASES1 represents bias array for layer 2, <i></i></div></div>=-4.01223725,1.21529032,-1.44377126,1.25407518,1.15038735,-1.49250311,-2.11001841,-0.9678679,-1.39067498,1.03981006,1.10141454,1.13101495
  <div class="tooltip">BIASES2<div class="right">bias array for each layer of the neural network, BIASES0 represents bias array for layer 1, BIASES1 represents bias array for layer 2, <i></i></div></div>=-0.1826424
... ANN
<br/><span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpfesfit">The ANN action with label <b>fesfit</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">fesfit.node</td><td>components of ANN outputs</td></tr></table></span><div class="tooltip" style="color:green">CUSTOM<div class="right">Calculate a combination of variables using a custom expression. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_u_s_t_o_m.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpfesfit">fesfit.node-0</b> <div class="tooltip">FUNC<div class="right">the function you wish to evaluate<i></i></div></div>=-1.0*x <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpwt" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpwt","data/p0.026/t0.8640-fes/plumed.inpwt","brown")'>wt</b>
<span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpwt">The CUSTOM action with label <b>wt</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">wt.value</td><td>an arbitrary function</td></tr></table></span><div class="tooltip" style="color:green">BIASVALUE<div class="right">Takes the value of one variable and use it as a bias <a href="https://www.plumed.org/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the scalar/vector arguments whose values will be used as a bias on the system<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpwt">wt</b> <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpb1" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpb1","data/p0.026/t0.8640-fes/plumed.inpb1","brown")'>b1</b>
<br/><span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpb1">The BIASVALUE action with label <b>b1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">b1.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">b1._bias</td><td>one or multiple instances of this quantity can be referenced elsewhere in the input file</td></tr></table></span><div class="tooltip" style="color:green">REWEIGHT_BIAS<div class="right">Calculate weights for ensemble averages that negate the effect the bias has on the region of phase space explored <a href="https://www.plumed.org/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__b_i_a_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">TEMP<div class="right">the system temperature<i></i></div></div>=0.8640 <div class="tooltip">ARG<div class="right"> the biases that must be taken into account when reweighting<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpb1">b1.bias</b> <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpbias" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpbias","data/p0.026/t0.8640-fes/plumed.inpbias","brown")'>bias</b>
<span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpbias">The REWEIGHT_BIAS action with label <b>bias</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">bias.value</td><td>the weight to use for this frame to negate the effect the bias</td></tr></table></span><div class="tooltip" style="color:green">REWEIGHT_GEOMFES<div class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_a_d.html" style="color:green">More details</a><i></i></div></div> TEMP=0.8640 ARG=<b name="data/p0.026/t0.8640-fes/plumed.inpcoord">coord.lessthan</b> LABEL=<b name="data/p0.026/t0.8640-fes/plumed.inpgd1" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpgd1","data/p0.026/t0.8640-fes/plumed.inpgd1","brown")'>gd1</b>
<br/><div class="tooltip" style="color:green">HISTOGRAM<div class="right">Accumulate the average probability density along a few CVs from a trajectory. <a href="https://www.plumed.org/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html" style="color:green">More details</a><i></i></div></div> ...
  <div class="tooltip">ARG<div class="right">the quantities that are being used to construct the histogram<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpcoord">coord.lessthan</b>
  <div class="tooltip">GRID_MIN<div class="right"> the lower bounds for the grid<i></i></div></div>=0
  <div class="tooltip">GRID_MAX<div class="right"> the upper bounds for the grid<i></i></div></div>=1000
  <div class="tooltip">GRID_BIN<div class="right">the number of bins for the grid<i></i></div></div>=1000
  <div class="tooltip">BANDWIDTH<div class="right">the bandwidths for kernel density esimtation<i></i></div></div>=10.0
  <div class="tooltip">LOGWEIGHTS<div class="right">the logarithm of the quantity to use as the weights when calculating averages<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpbias">bias</b>
  <div class="tooltip">STRIDE<div class="right"> the frequency with which to store data for averaging<i></i></div></div>=200
  <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inphh" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inphh","data/p0.026/t0.8640-fes/plumed.inphh","brown")'>hh</b>
... HISTOGRAM
<br/><span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inphh">The HISTOGRAM action with label <b>hh</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">hh.value</td><td>the estimate of the histogram as a function of the argument that was obtained</td></tr></table></span><div class="tooltip" style="color:green">HISTOGRAM<div class="right">Accumulate the average probability density along a few CVs from a trajectory. <a href="https://www.plumed.org/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html" style="color:green">More details</a><i></i></div></div> ...
  <div class="tooltip">ARG<div class="right">the quantities that are being used to construct the histogram<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpcoord">coord.lessthan</b>
  <div class="tooltip">GRID_MIN<div class="right"> the lower bounds for the grid<i></i></div></div>=0
  <div class="tooltip">GRID_MAX<div class="right"> the upper bounds for the grid<i></i></div></div>=1000
  <div class="tooltip">GRID_BIN<div class="right">the number of bins for the grid<i></i></div></div>=1000
  <div class="tooltip">BANDWIDTH<div class="right">the bandwidths for kernel density esimtation<i></i></div></div>=10.0
  <div class="tooltip">LOGWEIGHTS<div class="right">the logarithm of the quantity to use as the weights when calculating averages<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpbias">bias</b>,gd1
  <div class="tooltip">STRIDE<div class="right"> the frequency with which to store data for averaging<i></i></div></div>=200
  <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inphhg" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inphhg","data/p0.026/t0.8640-fes/plumed.inphhg","brown")'>hhg</b>
... HISTOGRAM
<br/><span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inphhg">The HISTOGRAM action with label <b>hhg</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">hhg.value</td><td>the estimate of the histogram as a function of the argument that was obtained</td></tr></table></span><div class="tooltip" style="color:green">HISTOGRAM<div class="right">Accumulate the average probability density along a few CVs from a trajectory. <a href="https://www.plumed.org/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html" style="color:green">More details</a><i></i></div></div> ...
  <div class="tooltip">ARG<div class="right">the quantities that are being used to construct the histogram<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpmolvol">molvol</b>
  <div class="tooltip">GRID_MIN<div class="right"> the lower bounds for the grid<i></i></div></div>=1.6
  <div class="tooltip">GRID_MAX<div class="right"> the upper bounds for the grid<i></i></div></div>=2.2
  <div class="tooltip">GRID_BIN<div class="right">the number of bins for the grid<i></i></div></div>=1200
  <div class="tooltip">BANDWIDTH<div class="right">the bandwidths for kernel density esimtation<i></i></div></div>=0.01
  <div class="tooltip">LOGWEIGHTS<div class="right">the logarithm of the quantity to use as the weights when calculating averages<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpbias">bias</b>
  <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inphhd" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inphhd","data/p0.026/t0.8640-fes/plumed.inphhd","brown")'>hhd</b>
... HISTOGRAM
<br/><span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inphhd">The HISTOGRAM action with label <b>hhd</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">hhd.value</td><td>the estimate of the histogram as a function of the argument that was obtained</td></tr></table></span><div class="tooltip" style="color:green">CONVERT_TO_FES<div class="right">Convert a histogram to a free energy surface. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">GRID<div class="right">the histogram that you would like to convert into a free energy surface (old syntax)<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inphh">hh</b>  <div class="tooltip">TEMP<div class="right">the temperature at which you are operating<i></i></div></div>=0.8640 <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpff" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpff","data/p0.026/t0.8640-fes/plumed.inpff","brown")'>ff</b>
<span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpff">The CONVERT_TO_FES action with label <b>ff</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">ff.value</td><td>the free energy surface</td></tr></table></span><div class="tooltip" style="color:green">CONVERT_TO_FES<div class="right">Convert a histogram to a free energy surface. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">GRID<div class="right">the histogram that you would like to convert into a free energy surface (old syntax)<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inphhg">hhg</b> <div class="tooltip">TEMP<div class="right">the temperature at which you are operating<i></i></div></div>=0.8640 <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpffg" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpffg","data/p0.026/t0.8640-fes/plumed.inpffg","brown")'>ffg</b>
<span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpffg">The CONVERT_TO_FES action with label <b>ffg</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">ffg.value</td><td>the free energy surface</td></tr></table></span><div class="tooltip" style="color:green">CONVERT_TO_FES<div class="right">Convert a histogram to a free energy surface. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">GRID<div class="right">the histogram that you would like to convert into a free energy surface (old syntax)<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inphhd">hhd</b> <div class="tooltip">TEMP<div class="right">the temperature at which you are operating<i></i></div></div>=0.8640 <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpffd" onclick='showPath("data/p0.026/t0.8640-fes/plumed.inp","data/p0.026/t0.8640-fes/plumed.inpffd","data/p0.026/t0.8640-fes/plumed.inpffd","brown")'>ffd</b>
<br/><span style="display:none;" id="data/p0.026/t0.8640-fes/plumed.inpffd">The CONVERT_TO_FES action with label <b>ffd</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">ffd.value</td><td>the free energy surface</td></tr></table></span><div class="tooltip" style="color:green">DUMPGRID<div class="right">Output the function on the grid to a file with the PLUMED grid format. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">GRID<div class="right">the grid you would like to print (can also use ARG for specifying what is being printed)<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpff">ff</b>  <div class="tooltip">FILE<div class="right"> the file on which to write the grid<i></i></div></div>=fes  <div class="tooltip">STRIDE<div class="right"> the frequency with which the grid should be output to the file<i></i></div></div>=2000000
<div class="tooltip" style="color:green">DUMPGRID<div class="right">Output the function on the grid to a file with the PLUMED grid format. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">GRID<div class="right">the grid you would like to print (can also use ARG for specifying what is being printed)<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpffg">ffg</b> <div class="tooltip">FILE<div class="right"> the file on which to write the grid<i></i></div></div>=fesg <div class="tooltip">STRIDE<div class="right"> the frequency with which the grid should be output to the file<i></i></div></div>=2000000
<div class="tooltip" style="color:green">DUMPGRID<div class="right">Output the function on the grid to a file with the PLUMED grid format. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">GRID<div class="right">the grid you would like to print (can also use ARG for specifying what is being printed)<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpffd">ffd</b> <div class="tooltip">FILE<div class="right"> the file on which to write the grid<i></i></div></div>=fesd <div class="tooltip">STRIDE<div class="right"> the frequency with which the grid should be output to the file<i></i></div></div>=2000000
<br/><div class="tooltip" style="color:green">FLUSH<div class="right">This command instructs plumed to flush all the open files with a user specified frequency. <a href="https://www.plumed.org/doc-master/user-doc/html/_f_l_u_s_h.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">STRIDE<div class="right">the frequency with which all the open files should be flushed<i></i></div></div>=2000
<div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=<b name="data/p0.026/t0.8640-fes/plumed.inpmolvol">molvol</b>,<b name="data/p0.026/t0.8640-fes/plumed.inpcoord">coord.lessthan</b>,<b name="data/p0.026/t0.8640-fes/plumed.inpb1">b1.bias</b> <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=200 <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=colvar
</pre>
{% endraw %}