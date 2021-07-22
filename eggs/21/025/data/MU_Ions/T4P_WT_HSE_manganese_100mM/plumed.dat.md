**Project ID:** [plumID:21.025]({{ '/' | absolute_url }}eggs/21/025/)  
**Source:** MU_Ions/T4P_WT_HSE_manganese_100mM/plumed.dat  
**Originally used with PLUMED version:** 2.6  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
d0: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=727,2885
d1: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=2791,4949
d2: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=4855,7013
d3: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=6974,478

uw: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=d0,d1,d2,d3 KAPPA=1000.0,1000.0,1000.0,1000.0 AT=2.5,2.7,2.5,2.0
lw: <a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html">LOWER_WALLS</a> ARG=d0,d1,d2,d3 KAPPA=1000.0,1000.0,1000.0,1000.0 AT=1.0,1.2,1.0,0.5

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> FILE=COLVAR ARG=d0,d1,d2,d3,uw.bias,lw.bias STRIDE=50000
</pre>{% endraw %}
