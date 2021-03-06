**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
**Source:** hbr/fes/plumed.inp  
**Originally used with PLUMED version:** 2.8  
**Stable:** [raw zipped stdout](plumed.inp.plumed.stdout.txt.zip) - [stderr](plumed.inp.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.inp.plumed_master.stdout.txt.zip) - [stderr](plumed.inp.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> LENGTH=A TIME=fs

d1: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=10,11 NOPBC
d2: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=11,1  NOPBC
d3: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=10,2  NOPBC
d4: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=11,2  NOPBC
d5: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=10,1  NOPBC
d6: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1,2   NOPBC

uwall: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=d1,d2,d3,d4,d5,d6 AT=3.0,3.0,3.0,3.0,3.0,3.0 KAPPA=100,100,100,100,100,100

cv: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> ARG=d1,d2,d3,d4,d5,d6 COEFFICIENTS=0.661,-0.656,-0.328,0.011,-0.021,0.157 PERIODIC=NO


<a href="https://plumed.github.io/doc-master/user-doc/html/_a_n_n.html">ANN</a> ...
  LABEL=fesfit
  ARG=cv
  NUM_LAYERS=3
  NUM_NODES=1,48,1
  ACTIVATIONS=Tanh,Linear
  WEIGHTS0=7.02603134,-7.10656245,6.87468804,6.44175163,-8.05901739,-9.92301921,8.70412179,5.24445234,-7.15034183,-4.89640601,5.23411097,-6.16335667,-5.80727531,6.09854222,9.03723364,-6.19909808,4.87341508,5.4844505,5.17560729,5.05697771,5.93438394,-5.71471957,-4.80556544,7.25557632,9.47419942,-4.59945602,6.16870363,8.73579702,-6.5963175,-3.4826426,6.87015659,4.32398507,-5.7119825,-3.62043586,5.52290261,-5.41269008,6.43750182,-4.61871456,6.61789092,4.69954468,8.29040765,-10.11716514,7.04612104,-5.44254231,4.57136333,-9.15486747,-4.94113593,6.71545542
  WEIGHTS1=-3.07574091,-9.89746009,-3.15299416,-3.24530278,-9.57739595,2.77604802,-3.4314115,-1.92436265,3.29843627,1.49236991,-2.84250541,-9.95369648,-9.3124519,-2.90663917,9.80867586,2.96358348,-1.62958348,-2.53223939,-2.79371778,-1.62894969,-3.27305257,2.6427191,1.48710888,-3.2627269,-3.67837903,-5.63907048,-2.36960156,-3.95901324,3.13753686,-9.23112732,-3.31650521,-0.72276839,2.75064713,-10.09041104,-2.92406711,2.72257186,-3.08722293,-5.56477804,-2.42215226,6.64587078,-3.33581553,3.29791456,-3.39129346,-9.53846615,-0.94354542,3.45900422,1.88059984,-2.90541763
  BIASES0=0.1902818,-4.10551933,0.22589334,-0.07582383,-3.50552854,-2.19018425,1.90013798,-1.35713566,-1.4730146,0.93418965,-0.69205605,-3.8355124,-6.29137461,-1.62394629,3.20821655,1.79014226,-0.93558303,-1.48051528,-0.78992735,-1.17037756,-0.24011175,2.67836642,0.87249589,0.15014032,2.08530087,-3.58209149,-1.6350707,1.90793108,0.03897141,3.48234302,0.22687527,-0.68752415,2.67617444,3.60703902,-2.49713368,3.77533027,0.41214063,-3.60686151,-4.82613345,3.70799175,1.79634271,-2.2350788,0.0519425,-4.51020721,-0.75313181,-2.009491,1.03992807,-0.01423335
  BIASES1=-10.3903018
... <a href="https://plumed.github.io/doc-master/user-doc/html/_a_n_n.html">ANN</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_c_u_s_t_o_m.html">CUSTOM</a> ARG=fesfit.node-0 FUNC=-1.0*(x-100) PERIODIC=NO LABEL=wt
<a href="https://plumed.github.io/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html">BIASVALUE</a> ARG=wt LABEL=b1
<a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__b_i_a_s.html">REWEIGHT_BIAS</a> TEMP=300 ARG=b1.bias LABEL=bias

<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=cv
  GRID_MIN=-2.0
  GRID_MAX=2.0
  GRID_BIN=4000
  BANDWIDTH=0.02
  LOGWEIGHTS=bias
  LABEL=hh
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh  TEMP=300.0 LABEL=ff

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff  FILE=fes  STRIDE=20000

<a href="https://plumed.github.io/doc-master/user-doc/html/_f_l_u_s_h.html">FLUSH</a> STRIDE=2000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=d1,d2,d3,d4,d5,d6,cv,b1.bias STRIDE=200 FILE=colvar
</pre>{% endraw %}
