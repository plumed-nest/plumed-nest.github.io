**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
**Source:** plumed_reweight/reweight_rho_hb.dat  
**Originally used with PLUMED version:** 2.6  
**Stable:** [zipped raw stdout](reweight_rho_hb.dat.plumed.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed.stderr.txt.zip) - [stderr](reweight_rho_hb.dat.plumed.stderr)  
**Master:** [zipped raw stdout](reweight_rho_hb.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed_master.stderr.txt.zip) - [stderr](reweight_rho_hb.dat.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/plumed_reweight/reweight_rho_hb.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="reweight_rho_hb.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="reweight_rho_hb.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></td></tr></table></div></div>
<pre style="width=97%;">
<b name="data/plumed_reweight/reweight_rho_hb.datrho" onclick='showPath("data/plumed_reweight/reweight_rho_hb.dat","data/plumed_reweight/reweight_rho_hb.datrho","data/plumed_reweight/reweight_rho_hb.datrho","brown")'>rho</b>: <div class="tooltip" style="color:green">READ<div class="right">Read quantities from a colvar file. <a href="https://www.plumed.org/doc-master/user-doc/html/_r_e_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">FILE<div class="right">the name of the file from which to read these quantities<i></i></div></div>=../test_data/rtp_coord.dat <div class="tooltip">VALUES<div class="right">the values to read from the file<i></i></div></div>=rho <div class="tooltip">IGNORE_FORCES<div class="right"> use this flag if the forces added by any bias can be safely ignored<i></i></div></div> <div class="tooltip">IGNORE_TIME<div class="right"> ignore the time in the colvar file<i></i></div></div>
<span style="display:none;" id="data/plumed_reweight/reweight_rho_hb.datrho">The READ action with label <b>rho</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">rho..#!custom</td><td>the names of the output components for this action depend on the actions input file see the example inputs below for details</td></tr></table></span><b name="data/plumed_reweight/reweight_rho_hb.dathb" onclick='showPath("data/plumed_reweight/reweight_rho_hb.dat","data/plumed_reweight/reweight_rho_hb.dathb","data/plumed_reweight/reweight_rho_hb.dathb","brown")'>hb</b>: <div class="tooltip" style="color:green">READ<div class="right">Read quantities from a colvar file. <a href="https://www.plumed.org/doc-master/user-doc/html/_r_e_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">FILE<div class="right">the name of the file from which to read these quantities<i></i></div></div>=../test_data/HB.dat <div class="tooltip">VALUES<div class="right">the values to read from the file<i></i></div></div>=hb <div class="tooltip">IGNORE_FORCES<div class="right"> use this flag if the forces added by any bias can be safely ignored<i></i></div></div> <div class="tooltip">IGNORE_TIME<div class="right"> ignore the time in the colvar file<i></i></div></div>
<span style="display:none;" id="data/plumed_reweight/reweight_rho_hb.dathb">The READ action with label <b>hb</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">hb..#!custom</td><td>the names of the output components for this action depend on the actions input file see the example inputs below for details</td></tr></table></span><b name="data/plumed_reweight/reweight_rho_hb.datmetad" onclick='showPath("data/plumed_reweight/reweight_rho_hb.dat","data/plumed_reweight/reweight_rho_hb.datmetad","data/plumed_reweight/reweight_rho_hb.datmetad","brown")'>metad</b>: <div class="tooltip" style="color:green">READ<div class="right">Read quantities from a colvar file. <a href="https://www.plumed.org/doc-master/user-doc/html/_r_e_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">FILE<div class="right">the name of the file from which to read these quantities<i></i></div></div>=../test_data/metad_data.dat <div class="tooltip">VALUES<div class="right">the values to read from the file<i></i></div></div>=metad <div class="tooltip">IGNORE_FORCES<div class="right"> use this flag if the forces added by any bias can be safely ignored<i></i></div></div> <div class="tooltip">IGNORE_TIME<div class="right"> ignore the time in the colvar file<i></i></div></div>
<br/><span style="display:none;" id="data/plumed_reweight/reweight_rho_hb.datmetad">The READ action with label <b>metad</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">metad..#!custom</td><td>the names of the output components for this action depend on the actions input file see the example inputs below for details</td></tr></table></span><b name="data/plumed_reweight/reweight_rho_hb.datweights" onclick='showPath("data/plumed_reweight/reweight_rho_hb.dat","data/plumed_reweight/reweight_rho_hb.datweights","data/plumed_reweight/reweight_rho_hb.datweights","brown")'>weights</b>: <div class="tooltip" style="color:green">REWEIGHT_METAD<div class="right">Calculate the weights configurations should contribute to the histogram in a simulation in which a metadynamics bias acts upon the system. <a href="https://www.plumed.org/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__m_e_t_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">TEMP<div class="right">the system temperature<i></i></div></div>=298 <div class="tooltip">ARG<div class="right"> the biases that must be taken into account when reweighting<i></i></div></div>=<b name="data/plumed_reweight/reweight_rho_hb.datmetad">metad.rbias</b>
<br/><span style="display:none;" id="data/plumed_reweight/reweight_rho_hb.datweights">The REWEIGHT_METAD action with label <b>weights</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">weights.value</td><td>the weight to use for this frame to negate the effect the metadynamics bias</td></tr></table></span><div class="tooltip" style="color:green">HISTOGRAM<div class="right">Accumulate the average probability density along a few CVs from a trajectory. <a href="https://www.plumed.org/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html" style="color:green">More details</a><i></i></div></div> ...
  <div class="tooltip">ARG<div class="right">the quantities that are being used to construct the histogram<i></i></div></div>=<b name="data/plumed_reweight/reweight_rho_hb.datrho">rho</b>,<b name="data/plumed_reweight/reweight_rho_hb.dathb">hb</b>
  <div class="tooltip">GRID_MIN<div class="right"> the lower bounds for the grid<i></i></div></div>=0,0
  <div class="tooltip">GRID_MAX<div class="right"> the upper bounds for the grid<i></i></div></div>=3.8,15
  <div class="tooltip">GRID_BIN<div class="right">the number of bins for the grid<i></i></div></div>=100,100
  <div class="tooltip">KERNEL<div class="right"> the kernel function you are using<i></i></div></div>=GAUSSIAN
  <div class="tooltip">BANDWIDTH<div class="right">the bandwidths for kernel density esimtation<i></i></div></div>=0.1,0.5
  <div class="tooltip">LOGWEIGHTS<div class="right">the logarithm of the quantity to use as the weights when calculating averages<i></i></div></div>=<b name="data/plumed_reweight/reweight_rho_hb.datweights">weights</b>
  <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/plumed_reweight/reweight_rho_hb.dathD" onclick='showPath("data/plumed_reweight/reweight_rho_hb.dat","data/plumed_reweight/reweight_rho_hb.dathD","data/plumed_reweight/reweight_rho_hb.dathD","brown")'>hD</b>
... HISTOGRAM
<br/><span style="display:none;" id="data/plumed_reweight/reweight_rho_hb.dathD">The HISTOGRAM action with label <b>hD</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">hD.value</td><td>the estimate of the histogram as a function of the argument that was obtained</td></tr></table></span><b name="data/plumed_reweight/reweight_rho_hb.datff" onclick='showPath("data/plumed_reweight/reweight_rho_hb.dat","data/plumed_reweight/reweight_rho_hb.datff","data/plumed_reweight/reweight_rho_hb.datff","brown")'>ff</b>: <div class="tooltip" style="color:green">CONVERT_TO_FES<div class="right">Convert a histogram to a free energy surface. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">GRID<div class="right">the histogram that you would like to convert into a free energy surface (old syntax)<i></i></div></div>=<b name="data/plumed_reweight/reweight_rho_hb.dathD">hD</b> <div class="tooltip">TEMP<div class="right">the temperature at which you are operating<i></i></div></div>=298
<span style="display:none;" id="data/plumed_reweight/reweight_rho_hb.datff">The CONVERT_TO_FES action with label <b>ff</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">ff.value</td><td>the free energy surface</td></tr></table></span><div class="tooltip" style="color:green">DUMPGRID<div class="right">Output the function on the grid to a file with the PLUMED grid format. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">GRID<div class="right">the grid you would like to print (can also use ARG for specifying what is being printed)<i></i></div></div>=<b name="data/plumed_reweight/reweight_rho_hb.datff">ff</b> <div class="tooltip">FILE<div class="right"> the file on which to write the grid<i></i></div></div>=ff_output.dat

<br/><span style="display:none;" id="data/plumed_reweight/reweight_rho_hb.dat">The DUMPGRID action with label <b></b> calculates something</span><div class="tooltip" style="color:green">ENDPLUMED<div class="right">Terminate plumed input. <a href="https://www.plumed.org/doc-master/user-doc/html/_e_n_d_p_l_u_m_e_d.html" style="color:green">More details</a><i></i></div></div><span style="color:blue" class="comment">
</span></pre>
{% endraw %}