**Project ID:** [plumID:21.031]({{ '/' | absolute_url }}eggs/21/031/)  
**Source:** plumed.dat  
**Originally used with PLUMED version:** 2.6  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#RESTART</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> LENGTH=A TIME=ps ENERGY=kcal/mol
<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=1-25214
nbd1: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=10888-11839,12285-14568 
nbd2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=21322-24882 
d: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=nbd1,nbd2 NOPBC

<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=d AT=60.0 KAPPA=300.0 EXP=2.0 EPS=1.0 OFFSET=0
<a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html">LOWER_WALLS</a> ARG=d AT=25.0 KAPPA=300.0 EXP=2.0 EPS=1.0 OFFSET=0
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
   LABEL=metad
   ARG=d PACE=500 HEIGHT=1.0 SIGMA=0.5 FILE=HILLS BIASFACTOR=20.0 TEMP=310.0
   GRID_MIN=24.0 GRID_MAX=61.0 GRID_BIN=150
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a>
<span style="color:blue"># monitor the variable and the metadynamics bias potential</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> STRIDE=100 ARG=d,metad.bias FILE=COLVAR


</pre>{% endraw %}
