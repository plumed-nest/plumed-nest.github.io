**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
**Source:** atlas_inputs/atlas_6d/pca_2/plumed.dat  
**Originally used with PLUMED version:** 2.7-mod  
**Stable:** [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}
<div style="width: 100%; float:left">
<div style="width: 90%; float:left" id="value_details_data/atlas_inputs/atlas_6d/pca_2/plumed.dat"> Click on the labels of the actions for more information on what each action computes </div>
<div style="width: 10%; float:left"><table><tr><td style="padding:1px"><a href="plumed.dat.plumed.stderr"><img src="https://img.shields.io/badge/v2.10-failed-red.svg" alt="tested onv2.10" /></a></td></tr><tr><td style="padding:1px"><a href="plumed.dat.plumed_master.stderr"><img src="https://img.shields.io/badge/master-failed-red.svg" alt="tested onmaster" /></a></td></tr></table></div></div>
<pre style="width=97%;">
<span style="color:blue" class="comment">#</span>
<div class="tooltip" style="color:green">UNITS<div class="right">This command sets the internal units for the code. <a href="https://www.plumed.org/doc-master/user-doc/html/_u_n_i_t_s.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">NATURAL<div class="right"> use natural units<i></i></div></div>
<br/><span style="display:none;" id="data/atlas_inputs/atlas_6d/pca_2/plumed.dat">The UNITS action with label <b></b> calculates something</span><b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd1" onclick='showPath("data/atlas_inputs/atlas_6d/pca_2/plumed.dat","data/atlas_inputs/atlas_6d/pca_2/plumed.datd1","data/atlas_inputs/atlas_6d/pca_2/plumed.datd1","brown")'>d1</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=1,2 <div class="tooltip">COMPONENTS<div class="right"> calculate the x, y and z components of the distance separately and store them as label<i></i></div></div>
<span style="display:none;" id="data/atlas_inputs/atlas_6d/pca_2/plumed.datd1">The DISTANCE action with label <b>d1</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">d1.x</td><td>the x-component of the vector connecting the two atoms</td></tr><tr><td width="5%">d1.y</td><td>the y-component of the vector connecting the two atoms</td></tr><tr><td width="5%">d1.z</td><td>the z-component of the vector connecting the two atoms</td></tr><tr><td width="5%">d1.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd2" onclick='showPath("data/atlas_inputs/atlas_6d/pca_2/plumed.dat","data/atlas_inputs/atlas_6d/pca_2/plumed.datd2","data/atlas_inputs/atlas_6d/pca_2/plumed.datd2","brown")'>d2</b>: <div class="tooltip" style="color:green">DISTANCE<div class="right">Calculate the distance between a pair of atoms. <a href="https://www.plumed.org/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ATOMS<div class="right">the pair of atom that we are calculating the distance between<i></i></div></div>=1,3 <div class="tooltip">COMPONENTS<div class="right"> calculate the x, y and z components of the distance separately and store them as label<i></i></div></div>
<br/><span style="display:none;" id="data/atlas_inputs/atlas_6d/pca_2/plumed.datd2">The DISTANCE action with label <b>d2</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">d2.x</td><td>the x-component of the vector connecting the two atoms</td></tr><tr><td width="5%">d2.y</td><td>the y-component of the vector connecting the two atoms</td></tr><tr><td width="5%">d2.z</td><td>the z-component of the vector connecting the two atoms</td></tr><tr><td width="5%">d2.value</td><td>the DISTANCE between this pair of atoms</td></tr></table></span><b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datff" onclick='showPath("data/atlas_inputs/atlas_6d/pca_2/plumed.dat","data/atlas_inputs/atlas_6d/pca_2/plumed.datff","data/atlas_inputs/atlas_6d/pca_2/plumed.datff","brown")'>ff</b>: <div class="tooltip" style="color:green">MATHEVAL<div class="right">An alias to the CUSTOM function that can also be used to calaculate combinations of variables using a custom expression. <a href="https://www.plumed.org/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the values input to this function<i></i></div></div>=<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd1">d1.x</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd1">d1.y</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd1">d1.z</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd2">d2.x</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd2">d2.y</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd2">d2.z</b> <div class="tooltip">VAR<div class="right">the names to give each of the arguments in the function<i></i></div></div>=x0,x1,x2,x3,x4,x5 <div class="tooltip">PERIODIC<div class="right">if the output of your function is periodic then you should specify the periodicity of the function<i></i></div></div>=NO <div class="tooltip">FUNC<div class="right">the function you wish to evaluate<i></i></div></div>=10.0*exp(-4.0*(x0-1.0)^2-4.0*(x1-1.0)^2-4.0*(x2-1.0)^2-4.0*(x3-1.0)^2-4.0*(x4-1.0)^2-4.0*(x5-1.0)^2)+10.0*exp(-4.0*(x0-1.0)^2-4.0*(x1-1.0)^2-4.0*(x2-1.0)^2-4.0*(x3-1.0)^2-4.0*(x4-1.0)^2-4.0*(x5+1.0)^2)+10.0*exp(-4.0*(x0-1.0)^2-4.0*(x1-1.0)^2-4.0*(x2-1.0)^2-4.0*(x3-1.0)^2-4.0*(x4+1.0)^2-4.0*(x5-1.0)^2)+10.0*exp(-4.0*(x0-1.0)^2-4.0*(x1-1.0)^2-4.0*(x2-1.0)^2-4.0*(x3+1.0)^2-4.0*(x4-1.0)^2-4.0*(x5+1.0)^2)+10.0*exp(-4.0*(x0-1.0)^2-4.0*(x1-1.0)^2-4.0*(x2+1.0)^2-4.0*(x3-1.0)^2-4.0*(x4+1.0)^2-4.0*(x5-1.0)^2)+10.0*exp(-4.0*(x0-1.0)^2-4.0*(x1+1.0)^2-4.0*(x2-1.0)^2-4.0*(x3+1.0)^2-4.0*(x4-1.0)^2-4.0*(x5+1.0)^2)+10.0*exp(-4.0*(x0+1.0)^2-4.0*(x1-1.0)^2-4.0*(x2+1.0)^2-4.0*(x3-1.0)^2-4.0*(x4+1.0)^2-4.0*(x5-1.0)^2)+10.0/(1.0/((5.0*x0+5.0)^2+(5.0*x1-5.0)^2+(5.0*x2+5.0)^2+(5.0*x3-5.0)^2+(5.0*x4+5.0)^2+(5.0*x5-5.0)^2+1)+1.0/((5.0*x0-5.0)^2+(5.0*x1+5.0)^2+(5.0*x2-5.0)^2+(5.0*x3+5.0)^2+(5.0*x4-5.0)^2+(5.0*x5+5.0)^2+1)+1.0/((5.0*x0-5.0)^2+(5.0*x1-5.0)^2+(5.0*x2+5.0)^2+(5.0*x3-5.0)^2+(5.0*x4+5.0)^2+(5.0*x5-5.0)^2+1)+1.0/((5.0*x0-5.0)^2+(5.0*x1-5.0)^2+(5.0*x2-5.0)^2+(5.0*x3+5.0)^2+(5.0*x4-5.0)^2+(5.0*x5+5.0)^2+1)+1.0/((5.0*x0-5.0)^2+(5.0*x1-5.0)^2+(5.0*x2-5.0)^2+(5.0*x3-5.0)^2+(5.0*x4+5.0)^2+(5.0*x5-5.0)^2+1)+1.0/((5.0*x0-5.0)^2+(5.0*x1-5.0)^2+(5.0*x2-5.0)^2+(5.0*x3-5.0)^2+(5.0*x4-5.0)^2+(5.0*x5+5.0)^2+1)+1.0/((5.0*x0-5.0)^2+(5.0*x1-5.0)^2+(5.0*x2-5.0)^2+(5.0*x3-5.0)^2+(5.0*x4-5.0)^2+(5.0*x5-5.0)^2+1)+1.0/((-2.04124145231931*x0-1.40824829046386*x1+1.40824829046386*x2-1.40824829046386*x3+1.40824829046386*x4+3.59175170953614*x5)^2.0+(-2.04124145231931*x0-1.40824829046386*x1+1.40824829046386*x2+3.59175170953614*x3+1.40824829046386*x4-1.40824829046386*x5)^2.0+(-2.04124145231931*x0+3.59175170953614*x1+1.40824829046386*x2-1.40824829046386*x3+1.40824829046386*x4-1.40824829046386*x5)^2.0+(-0.408248290463863*x0+0.408248290463863*x1-0.408248290463863*x2+0.408248290463863*x3-0.408248290463863*x4+0.408248290463863*x5)^8.0+(2.04124145231931*x0+1.40824829046386*x1-1.40824829046386*x2+1.40824829046386*x3+3.59175170953614*x4+1.40824829046386*x5)^2.0+(2.04124145231931*x0+1.40824829046386*x1+3.59175170953614*x2+1.40824829046386*x3-1.40824829046386*x4+1.40824829046386*x5)^2.0)+1.0/((-0.447213595499958*x1+0.447213595499958*x2-0.447213595499958*x3+0.447213595499958*x4-0.447213595499958*x5)^8.0+(-2.23606797749979*x0+1.0*x1-1.0*x2+1.0*x3+4.0*x4+1.0*x5+2.23606797749979)^2.0+(-2.23606797749979*x0+1.0*x1+4.0*x2+1.0*x3-1.0*x4+1.0*x5+2.23606797749979)^2.0+(2.23606797749979*x0-1.0*x1+1.0*x2-1.0*x3+1.0*x4+4.0*x5-2.23606797749979)^2.0+(2.23606797749979*x0-1.0*x1+1.0*x2+4.0*x3+1.0*x4-1.0*x5-2.23606797749979)^2.0+(2.23606797749979*x0+4.0*x1+1.0*x2-1.0*x3+1.0*x4-1.0*x5-2.23606797749979)^2.0)+1.0/((5.0*x1-5.0)^2.0+(-0.5*x2+0.5*x3-0.5*x4+0.5*x5)^8.0+(-2.5*x0+1.25*x2-1.25*x3+1.25*x4+3.75*x5+2.5)^2.0+(-2.5*x0+1.25*x2+3.75*x3+1.25*x4-1.25*x5+2.5)^2.0+(2.5*x0-1.25*x2+1.25*x3+3.75*x4+1.25*x5-2.5)^2.0+(2.5*x0+3.75*x2+1.25*x3-1.25*x4+1.25*x5-2.5)^2.0)+1.0/((5.0*x1-5.0)^2.0+(5.0*x3-5.0)^2.0+(5.0*x5-5.0)^2.0+(-0.577350269189626*x0-0.577350269189626*x2-0.577350269189626*x4)^8.0+(2.88675134594813*x0-3.94337567297407*x2+1.05662432702593*x4)^2.0+(2.88675134594813*x0+1.05662432702593*x2-3.94337567297407*x4)^2.0)+1.0/((5.0*x1-5.0)^2.0+(5.0*x2-5.0)^2.0+(-0.577350269189626*x3+0.577350269189626*x4-0.577350269189626*x5)^8.0+(-2.88675134594813*x0+1.66666666666667*x3+3.33333333333333*x4+1.66666666666667*x5+2.88675134594813)^2.0+(2.88675134594813*x0-1.66666666666667*x3+1.66666666666667*x4+3.33333333333333*x5-2.88675134594813)^2.0+(2.88675134594813*x0+3.33333333333333*x3+1.66666666666667*x4-1.66666666666667*x5-2.88675134594813)^2.0)+1.0/((5.0*x1-5.0)^2.0+(5.0*x2-5.0)^2.0+(5.0*x3-5.0)^2.0+(-0.707106781186548*x4+0.707106781186548*x5)^8.0+(-3.53553390593274*x0+2.5*x4+2.5*x5+3.53553390593274)^2.0+(3.53553390593274*x0+2.5*x4+2.5*x5-3.53553390593274)^2.0)+1.0/(1.0*(-x5)^8.0+(5.0*x0-5.0)^2.0+(5.0*x1-5.0)^2.0+(5.0*x2-5.0)^2.0+(5.0*x3-5.0)^2.0+(5.0*x4-5.0)^2.0

<br/><span style="display:none;" id="data/atlas_inputs/atlas_6d/pca_2/plumed.datff">The MATHEVAL action with label <b>ff</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">ff.value</td><td>an arbitrary function</td></tr></table></span><b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datbb" onclick='showPath("data/atlas_inputs/atlas_6d/pca_2/plumed.dat","data/atlas_inputs/atlas_6d/pca_2/plumed.datbb","data/atlas_inputs/atlas_6d/pca_2/plumed.datbb","brown")'>bb</b>: <div class="tooltip" style="color:green">BIASVALUE<div class="right">Takes the value of one variable and use it as a bias <a href="https://www.plumed.org/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the scalar/vector arguments whose values will be used as a bias on the system<i></i></div></div>=<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datff">ff</b>

<br/><span style="display:none;" id="data/atlas_inputs/atlas_6d/pca_2/plumed.datbb">The BIASVALUE action with label <b>bb</b> calculates the following quantities:<table  align="center" frame="void" width="95%" cellpadding="5%"><tr><td width="5%"><b> Quantity </b>  </td><td><b> Description </b> </td></tr><tr><td width="5%">bb.bias</td><td>the instantaneous value of the bias potential</td></tr><tr><td width="5%">bb._bias</td><td>one or multiple instances of this quantity can be referenced elsewhere in the input file</td></tr></table></span><b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datat" onclick='showPath("data/atlas_inputs/atlas_6d/pca_2/plumed.dat","data/atlas_inputs/atlas_6d/pca_2/plumed.datat","data/atlas_inputs/atlas_6d/pca_2/plumed.datat","brown")'>at</b>: <div class="tooltip" style="color:green">ATLAS<div class="right">This action is not part of PLUMED and was included by using a LOAD command <a href="https://www.plumed.org/doc-master/user-doc/html/_l_o_a_d.html" style="color:green">More details</a><i></i></div></div> ...
ARG=<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd1">d1.x</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd1">d1.y</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd1">d1.z</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd2">d2.x</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd2">d2.y</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd2">d2.z</b> REFERENCE=cluster.dat PACE=500
SIGMA=0.2 BIASFACTOR=15 HEIGHT=3.0
GRID_MAX=15.0 GRID_BIN=750 TEMP=1.0 TRUNCATE_GRIDS
REGULARISE=1E-11
ADAPTIVE_WALL=1.0
STATIC_WALL=0.0
...
<br/><div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=at,at_wtfact <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=at.gbias <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=500
<div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=at_adaptive_wall <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=at.wall <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=500
<div class="tooltip" style="color:green">PRINT<div class="right">Print quantities to a file. <a href="https://www.plumed.org/doc-master/user-doc/html/_p_r_i_n_t.html" style="color:green">More details</a><i></i></div></div> <div class="tooltip">ARG<div class="right">the labels of the values that you would like to print to the file<i></i></div></div>=<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd1">d1.x</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd1">d1.y</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd1">d1.z</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd2">d2.x</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd2">d2.y</b>,<b name="data/atlas_inputs/atlas_6d/pca_2/plumed.datd2">d2.z</b> <div class="tooltip">FILE<div class="right">the name of the file on which to output these quantities<i></i></div></div>=colvar <div class="tooltip">STRIDE<div class="right"> the frequency with which the quantities of interest should be output<i></i></div></div>=500
</pre>
{% endraw %}