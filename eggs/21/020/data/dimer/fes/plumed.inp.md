**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
**Source:** dimer/fes/plumed.inp  
**Originally used with PLUMED version:** 2.8  
**Stable:** [raw zipped stdout](plumed.inp.plumed.stdout.txt.zip) - [stderr](plumed.inp.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.inp.plumed_master.stdout.txt.zip) - [stderr](plumed.inp.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> NATURAL

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1,2 LABEL=dist

<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dist AT=7.0 KAPPA=1.0 LABEL=walls

<a href="https://plumed.github.io/doc-master/user-doc/html/_a_n_n.html">ANN</a> ...
  LABEL=fesfit
  ARG=dist
  NUM_LAYERS=3
  NUM_NODES=1,12,1
  ACTIVATIONS=Tanh,Linear
  WEIGHTS0=-1.10652425,-2.35390282,0.73520869,0.30508303,-1.91710758,-1.17080437,4.54476387,-1.55057519,-0.33438543,-0.51296629,-1.58933892,-0.66991935
  WEIGHTS1=1.12275159,-0.52419477,-1.68730803,0.54981566,-0.50883646,0.39913448,5.41323609,1.35671307,-0.83412662,0.09853493,2.40196946,-3.37362775
  BIASES0=0.92550763,-3.21503713,-2.65645714,-1.50841484,-3.84287814,0.98659592,-5.86437259,1.33560335,2.22786005,0.18571632,1.3609639,5.38428241
  BIASES1=1.14569644
... <a href="https://plumed.github.io/doc-master/user-doc/html/_a_n_n.html">ANN</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_c_u_s_t_o_m.html">CUSTOM</a> ARG=fesfit.node-0 FUNC=-1.0*x PERIODIC=NO LABEL=wt
<a href="https://plumed.github.io/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html">BIASVALUE</a> ARG=wt LABEL=b1
<a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__b_i_a_s.html">REWEIGHT_BIAS</a> TEMP=1.5 ARG=b1.bias LABEL=bias

<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=dist
  GRID_MIN=0.0
  GRID_MAX=8.0
  GRID_BIN=1600
  BANDWIDTH=0.1
  LOGWEIGHTS=bias
  LABEL=hh
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh  TEMP=1.5 LABEL=ff

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff  FILE=fes  STRIDE=1000000

<a href="https://plumed.github.io/doc-master/user-doc/html/_f_l_u_s_h.html">FLUSH</a> STRIDE=10000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=dist,b1.bias STRIDE=5000 FILE=colvar

</pre>{% endraw %}
