**Project ID:** [plumID:21.049]({{ '/' | absolute_url }}eggs/21/049/)  
**Source:** 3ad_cycle/plumed.4.dat  
**Originally used with PLUMED version:** 2.6  
**Stable:** [zipped raw stdout](plumed.4.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.4.dat.plumed.stderr.txt.zip) - [stderr](plumed.4.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.4.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.4.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.4.dat.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/3ad_cycle/plumed.4.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="plumed.4.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="plumed.4.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></td></tr><tr><td style="padding:1px"><img src="https://img.shields.io/badge/with-LOAD-yellow.svg" alt="tested on master" /></td></tr>
</table></div></div>
<pre style="width=97%;">
<div class="tooltip" style="color:green">LOAD<div class="right">Loads a library, possibly defining new actions. <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">FILE<div class="right">file to be loaded<i></i></div></div>=../PathCV.cpp
<span style="display:none;" id="data/3ad_cycle/plumed.4.dat">The LOAD action with label <b></b> calculates something</span><div class="tooltip" style="color:green">UNITS<div class="right">This command sets the internal units for the code. <a href="https://www.plumed.org/doc-master/user-doc/html/_u_n_i_t_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">LENGTH<div class="right">the units of lengths<i></i></div></div>=A <div class="tooltip">TIME<div class="right">the units of time<i></i></div></div>=ps <div class="tooltip">ENERGY<div class="right">the units of energy<i></i></div></div>=kcal/mol
<br/><b name="data/3ad_cycle/plumed.4.datphi" onclick='showPath("data/3ad_cycle/plumed.4.dat","data/3ad_cycle/plumed.4.datphi","data/3ad_cycle/plumed.4.datphi","brown")'>phi</b>: <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=5,7,9,15
<span style="display:none;" id="data/3ad_cycle/plumed.4.datphi">The TORSION action with label <b>phi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phi.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/3ad_cycle/plumed.4.datphic" onclick='showPath("data/3ad_cycle/plumed.4.dat","data/3ad_cycle/plumed.4.datphic","data/3ad_cycle/plumed.4.datphic","brown")'>phic</b>: <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=5,7,9,15 <div class="tooltip">COSINE<div class="right"> calculate cosine instead of dihedral<i></i></div></div>
<span style="display:none;" id="data/3ad_cycle/plumed.4.datphic">The TORSION action with label <b>phic</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phic.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/3ad_cycle/plumed.4.datphis" onclick='showPath("data/3ad_cycle/plumed.4.dat","data/3ad_cycle/plumed.4.datphis","data/3ad_cycle/plumed.4.datphis","brown")'>phis</b>: <div class="tooltip" style="color:green">CUSTOM<div class="right">Calculate a combination of variables using a custom expression. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_u_s_t_o_m.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/3ad_cycle/plumed.4.datphi">phi</b> <div class="tooltip">FUNC<div class="right">the function you wish to evaluate<i></i></div></div>=sin(x <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO
<br/><span style="display:none;" id="data/3ad_cycle/plumed.4.datphis">The CUSTOM action with label <b>phis</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">phis.value</td><td>an arbitrary function</td></tr></table></span><b name="data/3ad_cycle/plumed.4.datpsi" onclick='showPath("data/3ad_cycle/plumed.4.dat","data/3ad_cycle/plumed.4.datpsi","data/3ad_cycle/plumed.4.datpsi","brown")'>psi</b>: <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=7,9,15,17
<span style="display:none;" id="data/3ad_cycle/plumed.4.datpsi">The TORSION action with label <b>psi</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">psi.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/3ad_cycle/plumed.4.datpsic" onclick='showPath("data/3ad_cycle/plumed.4.dat","data/3ad_cycle/plumed.4.datpsic","data/3ad_cycle/plumed.4.datpsic","brown")'>psic</b>: <div class="tooltip" style="color:green">TORSION<div class="right">Calculate a torsional angle. <a href="https://www.plumed.org/doc-master/user-doc/html/_t_o_r_s_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the four atoms involved in the torsional angle<i></i></div></div>=7,9,15,17 <div class="tooltip">COSINE<div class="right"> calculate cosine instead of dihedral<i></i></div></div>
<span style="display:none;" id="data/3ad_cycle/plumed.4.datpsic">The TORSION action with label <b>psic</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">psic.value</td><td>the TORSION involving these atoms</td></tr></table></span><b name="data/3ad_cycle/plumed.4.datpsis" onclick='showPath("data/3ad_cycle/plumed.4.dat","data/3ad_cycle/plumed.4.datpsis","data/3ad_cycle/plumed.4.datpsis","brown")'>psis</b>: <div class="tooltip" style="color:green">CUSTOM<div class="right">Calculate a combination of variables using a custom expression. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_u_s_t_o_m.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/3ad_cycle/plumed.4.datpsi">psi</b> <div class="tooltip">FUNC<div class="right">the function you wish to evaluate<i></i></div></div>=sin(x <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO
<br/><span style="display:none;" id="data/3ad_cycle/plumed.4.datpsis">The CUSTOM action with label <b>psis</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">psis.value</td><td>an arbitrary function</td></tr></table></span><div class="tooltip" style="color:green">PATHCV<div class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_a_d.html" style="color:green">More details</a><i></i></div></div> LABEL=<b name="data/3ad_cycle/plumed.4.datpcv" onclick='showPath("data/3ad_cycle/plumed.4.dat","data/3ad_cycle/plumed.4.datpcv","data/3ad_cycle/plumed.4.datpcv","brown")'>pcv</b> ARG=<b name="data/3ad_cycle/plumed.4.datphic">phic</b>,<b name="data/3ad_cycle/plumed.4.datphis">phis</b>,<b name="data/3ad_cycle/plumed.4.datpsic">psic</b>,<b name="data/3ad_cycle/plumed.4.datpsis">psis</b> INFILE=in_cycle.input HALFLIFE=1000 PACE=250 WALKERS_RSTRIDE=250 WALKERS_ID=4 WALKERS_N=8 WALKERS_DIR
<br/><div class="tooltip" style="color:green">UPPER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=pcv.z <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=0.0  <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=50.0 <div class="tooltip">EXP<div class="right"> the powers for the walls<i></i></div></div>=2 <div class="tooltip">EPS<div class="right"> the values for s_i in the expression for a wall<i></i></div></div>=1 <div class="tooltip">OFFSET<div class="right"> the offset for the start of the wall<i></i></div></div>=0 <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/3ad_cycle/plumed.4.dattube" onclick='showPath("data/3ad_cycle/plumed.4.dat","data/3ad_cycle/plumed.4.dattube","data/3ad_cycle/plumed.4.dattube","brown")'>tube</b>
<br/><span style="display:none;" id="data/3ad_cycle/plumed.4.dattube">The UPPER_WALLS action with label <b>tube</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">tube.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">tube.force2</td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span><b name="data/3ad_cycle/plumed.4.datc" onclick='showPath("data/3ad_cycle/plumed.4.dat","data/3ad_cycle/plumed.4.datc","data/3ad_cycle/plumed.4.datc","brown")'>c</b>: <div class="tooltip" style="color:green">CONSTANT<div class="right">Create a constant value that can be passed to actions <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_n_s_t_a_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">VALUE<div class="right">the single number that you would like to store<i></i></div></div>=-1
<span style="display:none;" id="data/3ad_cycle/plumed.4.datc">The CONSTANT action with label <b>c</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">c.value</td><td>the constant value that was read from the plumed input</td></tr></table></span><b name="data/3ad_cycle/plumed.4.dats" onclick='showPath("data/3ad_cycle/plumed.4.dat","data/3ad_cycle/plumed.4.dats","data/3ad_cycle/plumed.4.dats","brown")'>s</b>: <div class="tooltip" style="color:green">COMBINE<div class="right">Calculate a polynomial combination of a set of other variables. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_o_m_b_i_n_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=pcv.s,<b name="data/3ad_cycle/plumed.4.datc">c</b> <div class="tooltip">COEFFICIENTS<div class="right"> the coefficients of the arguments in your function<i></i></div></div>=2.,1 <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=-1,1
<br/><span style="display:none;" id="data/3ad_cycle/plumed.4.dats">The COMBINE action with label <b>s</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">s.value</td><td>a linear compbination</td></tr></table></span><div class="tooltip" style="color:green">METAD<div class="right">Used to performed metadynamics on one or more collective variables. <a href="https://www.plumed.org/doc-master/user-doc/html/_m_e_t_a_d.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">LABEL<div class="right">a label for the action so that its output can be referenced in the input to other actions<i></i></div></div>=<b name="data/3ad_cycle/plumed.4.datmetad" onclick='showPath("data/3ad_cycle/plumed.4.dat","data/3ad_cycle/plumed.4.datmetad","data/3ad_cycle/plumed.4.datmetad","brown")'>metad</b> <div class="tooltip">ARG<div class="right">the labels of the scalars on which the bias will act<i></i></div></div>=<b name="data/3ad_cycle/plumed.4.dats">s</b> <div class="tooltip">HEIGHT<div class="right">the heights of the Gaussian hills<i></i></div></div>=0.08 <div class="tooltip">SIGMA<div class="right">the widths of the Gaussian hills<i></i></div></div>=0.05 <div class="tooltip">PACE<div class="right">the frequency for hill addition<i></i></div></div>=250 <div class="tooltip">WALKERS_RSTRIDE<div class="right">stride for reading hills files<i></i></div></div>=250 <div class="tooltip">WALKERS_ID<div class="right">walker id<i></i></div></div>=4 <div class="tooltip">WALKERS_N<div class="right">number of walkers<i></i></div></div>=7 <div class="tooltip">WALKERS_DIR<div class="right">shared directory with the hills files from all the walkers<i></i></div></div>
<br/><span style="display:none;" id="data/3ad_cycle/plumed.4.datmetad">The METAD action with label <b>metad</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">metad.bias</td><td>the instantaneous value of the bias potential</td></tr></table></span><div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=10 <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=<b name="data/3ad_cycle/plumed.4.datphic">phic</b>,<b name="data/3ad_cycle/plumed.4.datphis">phis</b>,<b name="data/3ad_cycle/plumed.4.datpsic">psic</b>,<b name="data/3ad_cycle/plumed.4.datpsis">psis</b>,<b name="data/3ad_cycle/plumed.4.datphi">phi</b>,<b name="data/3ad_cycle/plumed.4.datpsi">psi</b>,<b name="data/3ad_cycle/plumed.4.dats">s</b>,pcv.s,pcv.z,<b name="data/3ad_cycle/plumed.4.datmetad">metad.bias</b>,<b name="data/3ad_cycle/plumed.4.dattube">tube.bias</b> <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=<b name="data/3ad_cycle/plumed.4.dat">./COLVAR</b>
</pre>
{% endraw %}