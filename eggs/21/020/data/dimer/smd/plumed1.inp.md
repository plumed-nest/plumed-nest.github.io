**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
**Source:** dimer/smd/plumed1.inp  
**Originally used with PLUMED version:** 2.8  
**Stable:** [raw zipped stdout](plumed1.inp.plumed.stdout.txt.zip) - [stderr](plumed1.inp.plumed.stderr)  
**Master:** [raw zipped stdout](plumed1.inp.plumed_master.stdout.txt.zip) - [stderr](plumed1.inp.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> NATURAL

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1,2 LABEL=dist

<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dist AT=7.0 KAPPA=1.0 LABEL=walls

<a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_s_t_r_a_i_n_t.html">RESTRAINT</a> ARG=dist AT=0.8 KAPPA=1000.0 LABEL=res

<a href="https://plumed.github.io/doc-master/user-doc/html/_f_l_u_s_h.html">FLUSH</a> STRIDE=10000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=dist STRIDE=50 FILE=colvar

</pre>{% endraw %}
