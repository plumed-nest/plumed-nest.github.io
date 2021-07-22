**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
**Source:** sn2/fes/plumed.inp  
**Originally used with PLUMED version:** 2.8  
**Stable:** [raw zipped stdout](plumed.inp.plumed.stdout.txt.zip) - [stderr](plumed.inp.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.inp.plumed_master.stdout.txt.zip) - [stderr](plumed.inp.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> LENGTH=A TIME=fs

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1,2 LABEL=d1
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=2,6 LABEL=d2

<a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> ARG=d1,d2 COEFFICIENTS=0.707,-0.707 PERIODIC=NO LABEL=cv

<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=d1,d2 AT=5.0,5.0 KAPPA=100.0,100.0 LABEL=constrain

<a href="https://plumed.github.io/doc-master/user-doc/html/_a_n_n.html">ANN</a> ...
  LABEL=fesfit
  ARG=cv
  NUM_LAYERS=3
  NUM_NODES=1,12,1
  ACTIVATIONS=Tanh,Linear
  WEIGHTS0=3.56561455,-6.71040355,5.25044716,7.7231881,-7.91816755,-5.97251384,3.84144036,-4.82860899,-7.53180985,6.26159315,-4.12440194,4.40081403
  WEIGHTS1=7.89933249,5.06936118,3.93503597,3.88241017,-3.86538677,8.43184926,3.47606736,-3.72495959,6.24588806,3.35531128,4.67826819,-3.95806807
  BIASES0=-3.96371368,4.17326354,2.60848734,1.27662432,-2.49483138,1.35277058,2.71088811,-2.84712335,3.2062986,2.70329581,-4.1852847,5.51867405
  BIASES1=2.44193157
... <a href="https://plumed.github.io/doc-master/user-doc/html/_a_n_n.html">ANN</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_c_u_s_t_o_m.html">CUSTOM</a> ARG=fesfit.node-0 FUNC=-1.0*x PERIODIC=NO LABEL=wt
<a href="https://plumed.github.io/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html">BIASVALUE</a> ARG=wt LABEL=b1
<a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__b_i_a_s.html">REWEIGHT_BIAS</a> TEMP=300 ARG=b1.bias LABEL=bias

<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=cv
  GRID_MIN=-2.0
  GRID_MAX=2.0
  GRID_BIN=4000
  BANDWIDTH=0.05
  LOGWEIGHTS=bias
  LABEL=hh
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh  TEMP=300.0 LABEL=ff

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff  FILE=fes  STRIDE=20000

<a href="https://plumed.github.io/doc-master/user-doc/html/_f_l_u_s_h.html">FLUSH</a> STRIDE=2000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=cv,b1.bias STRIDE=200 FILE=colvar


</pre>{% endraw %}
