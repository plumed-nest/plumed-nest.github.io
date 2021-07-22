**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
**Source:** hbr/smd/plumed.inp  
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

<a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_v_i_n_g_r_e_s_t_r_a_i_n_t.html">MOVINGRESTRAINT</a> ...
  ARG=cv
  STEP0=0     AT0=-2.0  KAPPA0=10000.0
  STEP1=20000 AT1=1.0   KAPPA1=10000.0
  LABEL=res
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_v_i_n_g_r_e_s_t_r_a_i_n_t.html">MOVINGRESTRAINT</a>


<a href="https://plumed.github.io/doc-master/user-doc/html/_f_l_u_s_h.html">FLUSH</a> STRIDE=2000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=d1,d2,d3,d4,d5,d6,cv,res.work STRIDE=2 FILE=colvar


</pre>{% endraw %}
