**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
**Source:** dimer/smd/plumed2.inp  
**Originally used with PLUMED version:** 2.8  
**Stable:** [raw zipped stdout](plumed2.inp.plumed.stdout.txt.zip) - [stderr](plumed2.inp.plumed.stderr)  
**Master:** [raw zipped stdout](plumed2.inp.plumed_master.stdout.txt.zip) - [stderr](plumed2.inp.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> NATURAL

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1,2 LABEL=dist

<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dist AT=7.0 KAPPA=1.0 LABEL=walls

<a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_v_i_n_g_r_e_s_t_r_a_i_n_t.html">MOVINGRESTRAINT</a> ...
  ARG=dist
  STEP0=0       AT0=0.8  KAPPA0=1000.0
  STEP1=500000  AT1=8.0  KAPPA1=1000.0
  LABEL=res
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_v_i_n_g_r_e_s_t_r_a_i_n_t.html">MOVINGRESTRAINT</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_f_l_u_s_h.html">FLUSH</a> STRIDE=10000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=dist,res.work STRIDE=50 FILE=colvar

</pre>{% endraw %}
