**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
**Source:** hbr/fes/plumed.inp  
**Originally used with PLUMED version:** 2.8  
**Stable:** [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) - [stderr](plumed.inp.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) - [stderr](plumed.inp.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/hbr/fes/plumed.inp"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="plumed.inp.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="plumed.inp.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></td></tr></table></div></div>
<pre style="width=97%;">
<div class="tooltip" style="color:green">UNITS<div class="right">This command sets the internal units for the code. <a href="https://www.plumed.org/doc-master/user-doc/html/_u_n_i_t_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">LENGTH<div class="right">the units of lengths<i></i></div></div>=A <div class="tooltip">TIME<div class="right">the units of time<i></i></div></div>=fs
<br/><span style="display:none;" id="data/hbr/fes/plumed.inp">The UNITS action with label <b></b> calculates something</span><b name="data/hbr/fes/plumed.inpd1" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpd1","data/hbr/fes/plumed.inpd1","brown")'>d1</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=10,11 <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<span style="display:none;" id="data/hbr/fes/plumed.inpd1">The DISTANCE action with label <b>d1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">d1.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/hbr/fes/plumed.inpd2" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpd2","data/hbr/fes/plumed.inpd2","brown")'>d2</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=11,1  <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<span style="display:none;" id="data/hbr/fes/plumed.inpd2">The DISTANCE action with label <b>d2</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">d2.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/hbr/fes/plumed.inpd3" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpd3","data/hbr/fes/plumed.inpd3","brown")'>d3</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=10,2  <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<span style="display:none;" id="data/hbr/fes/plumed.inpd3">The DISTANCE action with label <b>d3</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">d3.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/hbr/fes/plumed.inpd4" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpd4","data/hbr/fes/plumed.inpd4","brown")'>d4</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=11,2  <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<span style="display:none;" id="data/hbr/fes/plumed.inpd4">The DISTANCE action with label <b>d4</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">d4.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/hbr/fes/plumed.inpd5" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpd5","data/hbr/fes/plumed.inpd5","brown")'>d5</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=10,1  <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<span style="display:none;" id="data/hbr/fes/plumed.inpd5">The DISTANCE action with label <b>d5</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">d5.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/hbr/fes/plumed.inpd6" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpd6","data/hbr/fes/plumed.inpd6","brown")'>d6</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=1,2   <div class="tooltip">NOPBC<div class="right"> ignore the periodic boundary conditions when calculating distances<i></i></div></div>
<br/><span style="display:none;" id="data/hbr/fes/plumed.inpd6">The DISTANCE action with label <b>d6</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">d6.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/hbr/fes/plumed.inpuwall" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpuwall","data/hbr/fes/plumed.inpuwall","brown")'>uwall</b>: <div class="tooltip" style="color:green">UPPER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=<b name="data/hbr/fes/plumed.inpd1">d1</b>,<b name="data/hbr/fes/plumed.inpd2">d2</b>,<b name="data/hbr/fes/plumed.inpd3">d3</b>,<b name="data/hbr/fes/plumed.inpd4">d4</b>,<b name="data/hbr/fes/plumed.inpd5">d5</b>,<b name="data/hbr/fes/plumed.inpd6">d6</b> <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=3.0,3.0,3.0,3.0,3.0,3.0 <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=100,100,100,100,100,100
<br/><span style="display:none;" id="data/hbr/fes/plumed.inpuwall">The UPPER_WALLS action with label <b>uwall</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">uwall.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">uwall.force2</td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span><b name="data/hbr/fes/plumed.inpcv" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpcv","data/hbr/fes/plumed.inpcv","brown")'>cv</b>: <div class="tooltip" style="color:green">COMBINE<div class="right">Calculate a polynomial combination of a set of other variables. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_m_b_i_n_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/hbr/fes/plumed.inpd1">d1</b>,<b name="data/hbr/fes/plumed.inpd2">d2</b>,<b name="data/hbr/fes/plumed.inpd3">d3</b>,<b name="data/hbr/fes/plumed.inpd4">d4</b>,<b name="data/hbr/fes/plumed.inpd5">d5</b>,<b name="data/hbr/fes/plumed.inpd6">d6</b> <div class="tooltip">COEFFICIENTS<div class="right"> the coefficients of the arguments in your function<i></i></div></div>=0.661,-0.656,-0.328,0.011,-0.021,0.157 <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO

<br/><span style="display:none;" id="data/hbr/fes/plumed.inpcv">The COMBINE action with label <b>cv</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">cv.value</td><td>a linear compbination</td></tr></table></span><div class="tooltip" style="color:green">ANN<div class="right">Calculates the ANN-function. <a href="https://www.plumed.org/doc-master/user-doc/html/_a_n_n.html" style="color:green">More details</a><i></i></div></div> ...
  <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/hbr/fes/plumed.inpfesfit" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpfesfit","data/hbr/fes/plumed.inpfesfit","brown")'>fesfit</b>
  <div class="tooltip">ARG<div class="right">the labels of the values from which the function is calculated<i></i></div></div>=<b name="data/hbr/fes/plumed.inpcv">cv</b>
  <div class="tooltip">NUM_LAYERS<div class="right">number of layers of the neural network<i></i></div></div>=3
  <div class="tooltip">NUM_NODES<div class="right">numbers of nodes in each layer of the neural network<i></i></div></div>=1,48,1
  <div class="tooltip">ACTIVATIONS<div class="right">activation functions for the neural network<i></i></div></div>=Tanh,Linear
  <div class="tooltip">WEIGHTS0<div class="right">flattened weight arrays connecting adjacent layers, WEIGHTS0 represents flattened weight array connecting layer 0 and layer 1, WEIGHTS1 represents flattened weight array connecting layer 1 and layer 2, <i></i></div></div>=7.02603134,-7.10656245,6.87468804,6.44175163,-8.05901739,-9.92301921,8.70412179,5.24445234,-7.15034183,-4.89640601,5.23411097,-6.16335667,-5.80727531,6.09854222,9.03723364,-6.19909808,4.87341508,5.4844505,5.17560729,5.05697771,5.93438394,-5.71471957,-4.80556544,7.25557632,9.47419942,-4.59945602,6.16870363,8.73579702,-6.5963175,-3.4826426,6.87015659,4.32398507,-5.7119825,-3.62043586,5.52290261,-5.41269008,6.43750182,-4.61871456,6.61789092,4.69954468,8.29040765,-10.11716514,7.04612104,-5.44254231,4.57136333,-9.15486747,-4.94113593,6.71545542
  <div class="tooltip">WEIGHTS1<div class="right">flattened weight arrays connecting adjacent layers, WEIGHTS0 represents flattened weight array connecting layer 0 and layer 1, WEIGHTS1 represents flattened weight array connecting layer 1 and layer 2, <i></i></div></div>=-3.07574091,-9.89746009,-3.15299416,-3.24530278,-9.57739595,2.77604802,-3.4314115,-1.92436265,3.29843627,1.49236991,-2.84250541,-9.95369648,-9.3124519,-2.90663917,9.80867586,2.96358348,-1.62958348,-2.53223939,-2.79371778,-1.62894969,-3.27305257,2.6427191,1.48710888,-3.2627269,-3.67837903,-5.63907048,-2.36960156,-3.95901324,3.13753686,-9.23112732,-3.31650521,-0.72276839,2.75064713,-10.09041104,-2.92406711,2.72257186,-3.08722293,-5.56477804,-2.42215226,6.64587078,-3.33581553,3.29791456,-3.39129346,-9.53846615,-0.94354542,3.45900422,1.88059984,-2.90541763
  <div class="tooltip">BIASES0<div class="right">bias array for each layer of the neural network, BIASES0 represents bias array for layer 1, BIASES1 represents bias array for layer 2, <i></i></div></div>=0.1902818,-4.10551933,0.22589334,-0.07582383,-3.50552854,-2.19018425,1.90013798,-1.35713566,-1.4730146,0.93418965,-0.69205605,-3.8355124,-6.29137461,-1.62394629,3.20821655,1.79014226,-0.93558303,-1.48051528,-0.78992735,-1.17037756,-0.24011175,2.67836642,0.87249589,0.15014032,2.08530087,-3.58209149,-1.6350707,1.90793108,0.03897141,3.48234302,0.22687527,-0.68752415,2.67617444,3.60703902,-2.49713368,3.77533027,0.41214063,-3.60686151,-4.82613345,3.70799175,1.79634271,-2.2350788,0.0519425,-4.51020721,-0.75313181,-2.009491,1.03992807,-0.01423335
  <div class="tooltip">BIASES1<div class="right">bias array for each layer of the neural network, BIASES0 represents bias array for layer 1, BIASES1 represents bias array for layer 2, <i></i></div></div>=-10.3903018
... ANN
<br/><span style="display:none;" id="data/hbr/fes/plumed.inpfesfit">The ANN action with label <b>fesfit</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">fesfit.node</td><td>components of ANN outputs</td></tr></table></span><div class="tooltip" style="color:green">CUSTOM<div class="right">Calculate a combination of variables using a custom expression. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_u_s_t_o_m.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/hbr/fes/plumed.inpfesfit">fesfit.node-0</b> <div class="tooltip">FUNC<div class="right">the function you wish to evaluate<i></i></div></div>=-1.0*(x-100 <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/hbr/fes/plumed.inpwt" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpwt","data/hbr/fes/plumed.inpwt","brown")'>wt</b>
<span style="display:none;" id="data/hbr/fes/plumed.inpwt">The CUSTOM action with label <b>wt</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">wt.value</td><td>an arbitrary function</td></tr></table></span><div class="tooltip" style="color:green">BIASVALUE<div class="right">Takes the value of one variable and use it as a bias <a href="https://www.plumed.org/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the scalar/vector arguments whose values will be used as a bias on the system<i></i></div></div>=<b name="data/hbr/fes/plumed.inpwt">wt</b> <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/hbr/fes/plumed.inpb1" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpb1","data/hbr/fes/plumed.inpb1","brown")'>b1</b>
<span style="display:none;" id="data/hbr/fes/plumed.inpb1">The BIASVALUE action with label <b>b1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">b1.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">b1._bias</td><td>one or multiple instances of this quantity can be referenced elsewhere in the input file</td></tr></table></span><div class="tooltip" style="color:green">REWEIGHT_BIAS<div class="right">Calculate weights for ensemble averages that negate the effect the bias has on the region of phase space explored <a href="https://www.plumed.org/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__b_i_a_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">TEMP<div class="right">the system temperature<i></i></div></div>=300 <div class="tooltip">ARG<div class="right"> the biases that must be taken into account when reweighting<i></i></div></div>=<b name="data/hbr/fes/plumed.inpb1">b1.bias</b> <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/hbr/fes/plumed.inpbias" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpbias","data/hbr/fes/plumed.inpbias","brown")'>bias</b>
<br/><span style="display:none;" id="data/hbr/fes/plumed.inpbias">The REWEIGHT_BIAS action with label <b>bias</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">bias.value</td><td>the weight to use for this frame to negate the effect the bias</td></tr></table></span><div class="tooltip" style="color:green">HISTOGRAM<div class="right">Accumulate the average probability density along a few CVs from a trajectory. <a href="https://www.plumed.org/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html" style="color:green">More details</a><i></i></div></div> ...
  <div class="tooltip">ARG<div class="right">the quantities that are being used to construct the histogram<i></i></div></div>=<b name="data/hbr/fes/plumed.inpcv">cv</b>
  <div class="tooltip">GRID_MIN<div class="right"> the lower bounds for the grid<i></i></div></div>=-2.0
  <div class="tooltip">GRID_MAX<div class="right"> the upper bounds for the grid<i></i></div></div>=2.0
  <div class="tooltip">GRID_BIN<div class="right">the number of bins for the grid<i></i></div></div>=4000
  <div class="tooltip">BANDWIDTH<div class="right">the bandwidths for kernel density esimtation<i></i></div></div>=0.02
  <div class="tooltip">LOGWEIGHTS<div class="right">the logarithm of the quantity to use as the weights when calculating averages<i></i></div></div>=<b name="data/hbr/fes/plumed.inpbias">bias</b>
  <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/hbr/fes/plumed.inphh" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inphh","data/hbr/fes/plumed.inphh","brown")'>hh</b>
... HISTOGRAM
<br/><span style="display:none;" id="data/hbr/fes/plumed.inphh">The HISTOGRAM action with label <b>hh</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">hh.value</td><td>the estimate of the histogram as a function of the argument that was obtained</td></tr></table></span><div class="tooltip" style="color:green">CONVERT_TO_FES<div class="right">Convert a histogram to a free energy surface. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">GRID<div class="right">the histogram that you would like to convert into a free energy surface (old syntax)<i></i></div></div>=<b name="data/hbr/fes/plumed.inphh">hh</b>  <div class="tooltip">TEMP<div class="right">the temperature at which you are operating<i></i></div></div>=300.0 <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/hbr/fes/plumed.inpff" onclick='showPath("data/hbr/fes/plumed.inp","data/hbr/fes/plumed.inpff","data/hbr/fes/plumed.inpff","brown")'>ff</b>
<br/><span style="display:none;" id="data/hbr/fes/plumed.inpff">The CONVERT_TO_FES action with label <b>ff</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">ff.value</td><td>the free energy surface</td></tr></table></span><div class="tooltip" style="color:green">DUMPGRID<div class="right">Output the function on the grid to a file with the PLUMED grid format. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">GRID<div class="right">the grid you would like to print (can also use ARG for specifying what is being printed)<i></i></div></div>=<b name="data/hbr/fes/plumed.inpff">ff</b>  <div class="tooltip">FILE<div class="right"> the file on which to write the grid<i></i></div></div>=fes  <div class="tooltip">STRIDE<div class="right"> the frequency with which the grid should be output to the file<i></i></div></div>=20000
<br/><div class="tooltip" style="color:green">FLUSH<div class="right">This command instructs plumed to flush all the open files with a user specified frequency. <a href="https://www.plumed.org/doc-master/user-doc/html/_f_l_u_s_h.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">STRIDE<div class="right">the frequency with which all the open files should be flushed<i></i></div></div>=2000
<div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=<b name="data/hbr/fes/plumed.inpd1">d1</b>,<b name="data/hbr/fes/plumed.inpd2">d2</b>,<b name="data/hbr/fes/plumed.inpd3">d3</b>,<b name="data/hbr/fes/plumed.inpd4">d4</b>,<b name="data/hbr/fes/plumed.inpd5">d5</b>,<b name="data/hbr/fes/plumed.inpd6">d6</b>,<b name="data/hbr/fes/plumed.inpcv">cv</b>,<b name="data/hbr/fes/plumed.inpb1">b1.bias</b> <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=200 <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=colvar
</pre>
{% endraw %}