**Project ID:** [plumID:21.032]({{ '/' | absolute_url }}eggs/21/032/)  
**Source:** plumed_water.dat  
**Originally used with PLUMED version:** 2.6  
**Stable:** [raw zipped stdout](plumed_water.dat.plumed.stdout.txt.zip) - [stderr](plumed_water.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed_water.dat.plumed_master.stdout.txt.zip) - [stderr](plumed_water.dat.plumed_master.stderr)  

{% raw %}<pre>


<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=1-781 STRIDE=1

metad:       <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_a_d.html">READ</a> FILE=COLVAR_REWEIGHT_sol IGNORE_TIME VALUES=metad.bias
weights1: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__b_i_a_s.html">REWEIGHT_BIAS</a> TEMP=300 ARG=metad.bias

WAT: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=782-23020:3

WAT64:  <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> SWITCH={RATIONAL R_0=0.29 D_MAX=0.5 NN=12 MM=24} GROUPA=WAT GROUPB=776 




Cys: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=67,88,243,292,152,324,173,211,359,465,455,628,434,512,554,761,599,424,751,730


coord64: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a>  GROUPA=Cys GROUPB=776 SWITCH={RATIONAL R_0=0.315 D_MAX=0.5 NN=12 MM=24}


<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
   ARG=coord64,WAT64
   GRID_MIN=0,0
   GRID_MAX=6,8
   GRID_BIN=300,300
   BANDWIDTH=0.05,0.05
   LABEL=h64
LOGWEIGHTS=weights1
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>


<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=h64 FILE=histo_wall FMT=%24.16e

fes64: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=h64 TEMP=300
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=fes64 FILE=fes64opt.dat FMT=%8.4f

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> STRIDE=1 ARG=* FILE=COLVAR_coor_optim
</pre>{% endraw %}
