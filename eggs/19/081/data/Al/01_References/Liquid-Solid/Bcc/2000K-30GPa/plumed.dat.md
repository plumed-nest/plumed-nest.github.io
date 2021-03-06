**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
**Source:** Al/01_References/Liquid-Solid/Bcc/2000K-30GPa/plumed.dat  
**Originally used with PLUMED version:** 2.6-dev  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue"># <a href="https://plumed.github.io/doc-master/user-doc/html/_vim_syntax.html">vim:ft=plumed</a></span>

<a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_s_t_a_r_t.html">RESTART</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_a_d.html">LOAD</a> FILE=../../../../../RefCV.cpp

energy: <a href="https://plumed.github.io/doc-master/user-doc/html/_e_n_e_r_g_y.html">ENERGY</a>

vol: <a href="https://plumed.github.io/doc-master/user-doc/html/_v_o_l_u_m_e.html">VOLUME</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_f_c_v.html">REFCV</a> ...
 SPECIES=1-250
 SIGMA=0.045
 LATTICE_CONSTANTS=0.3
 CRYSTAL_STRUCTURE=BCC
 LABEL=refcv
 MORE_THAN={RATIONAL R_0=0.5 NN=12 MM=24}
 MEAN
... <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_f_c_v.html">REFCV</a>

<span style="color:blue"># Construct a bias potential using VES</span>
<span style="color:blue">#</span>
<span style="color:blue"># Basis functions</span>

bf1: <a href="https://plumed.github.io/doc-master/user-doc/html/_b_f__l_e_g_e_n_d_r_e.html">BF_LEGENDRE</a> ORDER=20 MINIMUM=0.0 MAXIMUM=250.0

<span style="color:blue"># Target distribution</span>
td_welltemp: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_d__w_e_l_l_t_e_m_p_e_r_e_d.html">TD_WELLTEMPERED</a> BIASFACTOR=200

<span style="color:blue"># Expansion</span>

<a href="https://plumed.github.io/doc-master/user-doc/html/_v_e_s__l_i_n_e_a_r__e_x_p_a_n_s_i_o_n.html">VES_LINEAR_EXPANSION</a> ...
 ARG=refcv.morethan
 BASIS_FUNCTIONS=bf1
 TEMP=2000.0
 GRID_BINS=300
 TARGET_DISTRIBUTION=td_welltemp
 LABEL=b1
... <a href="https://plumed.github.io/doc-master/user-doc/html/_v_e_s__l_i_n_e_a_r__e_x_p_a_n_s_i_o_n.html">VES_LINEAR_EXPANSION</a>

<span style="color:blue"># Optimization algorithm</span>

<a href="https://plumed.github.io/doc-master/user-doc/html/_o_p_t__d_u_m_m_y.html">OPT_DUMMY</a> ...
  BIAS=b1
  STRIDE=500
  LABEL=o1
  COEFFS_OUTPUT=10
... <a href="https://plumed.github.io/doc-master/user-doc/html/_o_p_t__d_u_m_m_y.html">OPT_DUMMY</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_q6.html">Q6</a> SPECIES=1-250 SWITCH={CUBIC D_0=0.25 D_MAX=0.35} VMEAN LABEL=q6
diff: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=q6.vmean,refcv.mean FUNC=(x-0.0652)/(0.4167-0.0652)-(y-0.3232)/(0.7579-0.3232) PERIODIC=NO
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=diff AT=0.05 KAPPA=500000 EXP=2 LABEL=uwall

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=* FILE=COLVAR STRIDE=500
</pre>{% endraw %}
