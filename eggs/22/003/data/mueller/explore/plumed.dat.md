**Project ID:** [plumID:22.003]({{ '/' | absolute_url }}eggs/22/003/)  
**Source:** mueller/explore/plumed.dat  
**Originally used with PLUMED version:** 2.8  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/mueller/explore/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-passing-green.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-passing-green.svg" alt="tested onmaster" /></a></td></tr></table></div></div>
<pre style="width=97%;">
<div class="tooltip" style="color:blue"># vim:ft=plumed<div class="right">Enables syntax highlighting for PLUMED files in vim. See <a href="https://www.plumed.org/doc-master/user-doc/html/_vim_syntax.html">here for more details. </a><i></i></div></div>
<div class="tooltip" style="color:green">UNITS<div class="right">This command sets the internal units for the code. <a href="https://www.plumed.org/doc-master/user-doc/html/_u_n_i_t_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">NATURAL<div class="right"> use natural units<i></i></div></div>
<br/><span style="display:none;" id="data/mueller/explore/plumed.dat">The UNITS action with label <b></b> calculates something</span><b name="data/mueller/explore/plumed.datp" onclick='showPath("data/mueller/explore/plumed.dat","data/mueller/explore/plumed.datp","data/mueller/explore/plumed.datp","black")'>p</b><span style="display:none;" id="data/mueller/explore/plumed.datp">The POSITION action with label <b>p</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">p.x</td><td width="5%"><font color="black">scalar</font></td><td>the x-component of the atom position</td></tr><tr><td width="5%">p.y</td><td width="5%"><font color="black">scalar</font></td><td>the y-component of the atom position</td></tr><tr><td width="5%">p.z</td><td width="5%"><font color="black">scalar</font></td><td>the z-component of the atom position</td></tr></table></span>: <div class="tooltip" style="color:green">POSITION<div class="right">Calculate the components of the position of an atom. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_o_s_i_t_i_o_n.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOM<div class="right">the atom number<i></i></div></div>=1
<b name="data/mueller/explore/plumed.datmueller" onclick='showPath("data/mueller/explore/plumed.dat","data/mueller/explore/plumed.datmueller","data/mueller/explore/plumed.datmueller","black")'>mueller</b><span style="display:none;" id="data/mueller/explore/plumed.datmueller">The CUSTOM action with label <b>mueller</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">mueller</td><td width="5%"><font color="black">scalar</font></td><td>an arbitrary function</td></tr></table></span>: <div class="tooltip" style="color:green">CUSTOM<div class="right">Calculate a combination of variables using a custom expression. <a href="https://www.plumed.org/doc-master/user-doc/html/_c_u_s_t_o_m.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/mueller/explore/plumed.datp">p.x</b>,<b name="data/mueller/explore/plumed.datp">p.y</b> <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO ...
  <div class="tooltip">FUNC<div class="right">the function you wish to evaluate<i></i></div></div>=0.15*(-200*exp(-(x-1)^2-10*y^2)-100*exp(-x^2-10*(y-0.5)^2)-170*exp(-6.5*(0.5+x)^2+11*(x+0.5)*(y-1.5)-6.5*(y-1.5)^2)+15*exp(0.7*(1+x)^2+0.6*(x+1)*(y-1)+0.7*(y-1)^2)+146.7
...
<b name="data/mueller/explore/plumed.datpotential" onclick='showPath("data/mueller/explore/plumed.dat","data/mueller/explore/plumed.datpotential","data/mueller/explore/plumed.datpotential","black")'>potential</b><span style="display:none;" id="data/mueller/explore/plumed.datpotential">The BIASVALUE action with label <b>potential</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">potential.bias</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">potential.mueller_bias</td><td width="5%"><font color="black">scalar</font></td><td>one or multiple instances of this quantity can be referenced elsewhere in the input file. these quantities will named with  the arguments of the bias followed by the character string _bias. These quantities tell the user how much the bias is due to each of the colvars. This particular component measures this quantity for the input CV named mueller</td></tr></table></span>: <div class="tooltip" style="color:green">BIASVALUE<div class="right">Takes the value of one variable and use it as a bias <a href="https://www.plumed.org/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the scalar/vector arguments whose values will be used as a bias on the system<i></i></div></div>=<b name="data/mueller/explore/plumed.datmueller">mueller</b>
<b name="data/mueller/explore/plumed.datlwall" onclick='showPath("data/mueller/explore/plumed.dat","data/mueller/explore/plumed.datlwall","data/mueller/explore/plumed.datlwall","black")'>lwall</b><span style="display:none;" id="data/mueller/explore/plumed.datlwall">The LOWER_WALLS action with label <b>lwall</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">lwall.bias</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">lwall.force2</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span>: <div class="tooltip" style="color:green">LOWER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=<b name="data/mueller/explore/plumed.datp">p.x</b> <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=1000 <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=-1.3
<b name="data/mueller/explore/plumed.datuwall" onclick='showPath("data/mueller/explore/plumed.dat","data/mueller/explore/plumed.datuwall","data/mueller/explore/plumed.datuwall","black")'>uwall</b><span style="display:none;" id="data/mueller/explore/plumed.datuwall">The UPPER_WALLS action with label <b>uwall</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">uwall.bias</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">uwall.force2</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the squared force due to this bias potential</td></tr></table></span>: <div class="tooltip" style="color:green">UPPER_WALLS<div class="right">Defines a wall for the value of one or more collective variables, <a href="https://www.plumed.org/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the arguments on which the bias is acting<i></i></div></div>=<b name="data/mueller/explore/plumed.datp">p.x</b> <div class="tooltip">KAPPA<div class="right">the force constant for the wall<i></i></div></div>=1000 <div class="tooltip">AT<div class="right">the positions of the wall<i></i></div></div>=+1.0
<br/><span id="data/mueller/explore/plumed.datdefopes_short"><b name="data/mueller/explore/plumed.datopes" onclick='showPath("data/mueller/explore/plumed.dat","data/mueller/explore/plumed.datopes","data/mueller/explore/plumed.datopes","black")'>opes</b><span style="display:none;" id="data/mueller/explore/plumed.datopes">The OPES_METAD_EXPLORE action with label <b>opes</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td width="5%"><b> Type </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">opes.bias</td><td width="5%"><font color="black">scalar</font></td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">opes.rct</td><td width="5%"><font color="black">scalar</font></td><td>estimate of c(t). log(exp(beta V)/beta, should become flat as the simulation converges. Do NOT use for reweighting</td></tr><tr><td width="5%">opes.zed</td><td width="5%"><font color="black">scalar</font></td><td>estimate of Z_n. should become flat once no new CV-space region is explored</td></tr><tr><td width="5%">opes.neff</td><td width="5%"><font color="black">scalar</font></td><td>effective sample size</td></tr><tr><td width="5%">opes.nker</td><td width="5%"><font color="black">scalar</font></td><td>total number of compressed kernels used to represent the bias</td></tr></table></span>: <div class="tooltip" style="color:green">OPES_METAD_EXPLORE<div class="right">On-the-fly probability enhanced sampling with well-tempered target distribution in exploreation mode. This action has <a class="toggler" href='javascript:;' onclick='toggleDisplay("data/mueller/explore/plumed.datdefopes");'>hidden defaults</a>. <a href="https://www.plumed.org/doc-master/user-doc/html/_o_p_e_s__m_e_t_a_d__e_x_p_l_o_r_e.html">More details</a><i></i></div></div> ...
  <div class="tooltip">ARG<div class="right">the labels of the scalars on which the bias will act<i></i></div></div>=<b name="data/mueller/explore/plumed.datp">p.x</b>
  <div class="tooltip">PACE<div class="right">the frequency for kernel deposition<i></i></div></div>=500
  <div class="tooltip">BARRIER<div class="right">the free energy barrier to be overcome<i></i></div></div>=20
...
</span><span id="data/mueller/explore/plumed.datdefopes_long" style="display:none;"><b name="data/mueller/explore/plumed.datopes" onclick='showPath("data/mueller/explore/plumed.dat","data/mueller/explore/plumed.datopes","data/mueller/explore/plumed.datopes","black")'>opes</b>: <div class="tooltip" style="color:green">OPES_METAD_EXPLORE<div class="right">On-the-fly probability enhanced sampling with well-tempered target distribution in exploreation mode. This action uses the <a class="toggler" href='javascript:;' onclick='toggleDisplay("data/mueller/explore/plumed.datdefopes");'>defaults shown here</a>. <a href="https://www.plumed.org/doc-master/user-doc/html/_o_p_e_s__m_e_t_a_d__e_x_p_l_o_r_e.html">More details</a><i></i></div></div> ...
  <div class="tooltip">ARG<div class="right">the labels of the scalars on which the bias will act<i></i></div></div>=<b name="data/mueller/explore/plumed.datp">p.x</b>
  <div class="tooltip">PACE<div class="right">the frequency for kernel deposition<i></i></div></div>=500
  <div class="tooltip">BARRIER<div class="right">the free energy barrier to be overcome<i></i></div></div>=20
 <div class="tooltip">TEMP<div class="right"> temperature<i></i></div></div>=-1 <div class="tooltip">SIGMA<div class="right"> the initial widths of the kernels, divided by the square root of gamma<i></i></div></div>=ADAPTIVE <div class="tooltip">COMPRESSION_THRESHOLD<div class="right"> merge kernels if closer than this threshold, in units of sigma<i></i></div></div>=1 <div class="tooltip">FILE<div class="right"> a file in which the list of all deposited kernels is stored<i></i></div></div>=KERNELS
...
</span><br/><div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">FMT<div class="right">the format that should be used to output real numbers<i></i></div></div>=%g <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=500 <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=COLVAR <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=<b name="data/mueller/explore/plumed.datp">p.x</b>,<b name="data/mueller/explore/plumed.datp">p.y</b>,<b name="data/mueller/explore/plumed.datmueller">mueller</b>,<b name="data/mueller/explore/plumed.datopes">opes</b>
<br/><div class="tooltip" style="color:green">ENDPLUMED<div class="right">Terminate plumed input. <a href="https://www.plumed.org/doc-master/user-doc/html/_e_n_d_p_l_u_m_e_d.html" style="color:green">More details</a><i></i></div></div><span style="color:blue" class="comment">

run with:
mkdir $i
../../queue_md.i.sh $i

or
../loop_all.sh
</span></pre>
{% endraw %}