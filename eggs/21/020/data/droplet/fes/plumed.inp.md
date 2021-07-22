**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
**Source:** droplet/fes/plumed.inp  
**Originally used with PLUMED version:** 2.8  
**Stable:** [raw zipped stdout](plumed.inp.plumed.stdout.txt.zip) - [stderr](plumed.inp.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.inp.plumed_master.stdout.txt.zip) - [stderr](plumed.inp.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> LENGTH=A

<a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_a_d.html">LOAD</a> FILE=./ReweightGeomFES.cpp

<a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> ...
  LABEL=coord
  SPECIES=1-512
  SWITCH={RATIONAL R_0=5.0 D_MAX=10.0}
  MORE_THAN={RATIONAL R_0=5.0 D_MAX=5.5}
  LOWMEM
... <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=coord.morethan AT=64 KAPPA=1.0 LABEL=wall

<a href="https://plumed.github.io/doc-master/user-doc/html/_a_n_n.html">ANN</a> ...
  LABEL=fesfit
  ARG=coord.morethan
  NUM_LAYERS=3
  NUM_NODES=1,12,1
  ACTIVATIONS=Tanh,Linear
  WEIGHTS0=0.9058232,-0.90187826,0.3208892,0.37238594,-0.61194702,-0.06594427,1.70867385,-0.31515388,-0.4163217,0.28925027,0.18196869,-0.31543091
  WEIGHTS1=0.60805163,0.35438915,0.08615935,0.34359914,0.18291669,3.01964527,0.38431888,-0.07582409,-0.35502226,0.3090121,0.30355232,-0.43806144
  BIASES0=-1.71557585,-2.35374153,-1.66746451,-2.24434536,-1.54600118,3.66541523,-1.79000195,1.5943394,2.66015844,-1.51256678,-0.0384513,4.48851321
  BIASES1=0.39086608
... <a href="https://plumed.github.io/doc-master/user-doc/html/_a_n_n.html">ANN</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_c_u_s_t_o_m.html">CUSTOM</a> ARG=fesfit.node-0 FUNC=-1.0*x PERIODIC=NO LABEL=wt
<a href="https://plumed.github.io/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html">BIASVALUE</a> ARG=wt LABEL=b1
<a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__b_i_a_s.html">REWEIGHT_BIAS</a> TEMP=80.7 ARG=b1.bias LABEL=bias
<a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__g_e_o_m_f_e_s.html">REWEIGHT_GEOMFES</a> TEMP=80.7 ARG=coord.morethan LABEL=gd1

<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=coord.morethan
  GRID_MIN=-0.5
  GRID_MAX=64
  GRID_BIN=6450
  BANDWIDTH=0.2
  LOGWEIGHTS=bias
  LABEL=hh
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=coord.morethan
  GRID_MIN=-0.5
  GRID_MAX=64
  GRID_BIN=6450
  BANDWIDTH=0.2
  LOGWEIGHTS=bias,gd1
  LABEL=hhg
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh  TEMP=80.7 LABEL=ff
<a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hhg TEMP=80.7 LABEL=ffg

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff  FILE=fes  STRIDE=10000000
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ffg FILE=fesg STRIDE=10000000

<a href="https://plumed.github.io/doc-master/user-doc/html/_f_l_u_s_h.html">FLUSH</a> STRIDE=200000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=coord.morethan,b1.bias STRIDE=2000 FILE=colvar

</pre>{% endraw %}
