**Project ID:** [plumID:21.029]({{ '/' | absolute_url }}eggs/21/029/)  
**Source:** ala3/parallel/plumed.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_l_i_n_f_o.html">MOLINFO</a> MOLTYPE=protein STRUCTURE=ala3.pdb
<a href="https://plumed.github.io/doc-master/user-doc/html/_f_l_u_s_h.html">FLUSH</a> STRIDE=500

energy: <a href="https://plumed.github.io/doc-master/user-doc/html/_e_n_e_r_g_y.html">ENERGY</a> 
phi1:   <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=5,7,9,15       NOPBC
psi1:   <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=7,9,15,17      NOPBC
phi2:   <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=15,17,19,25    NOPBC
psi2:   <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=17,19,25,27    NOPBC
phi3:   <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=25,27,29,35    NOPBC
psi3:   <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=27,29,35,37    NOPBC

<a href="https://plumed.github.io/doc-master/user-doc/html/_e_x_t_e_r_n_a_l.html">EXTERNAL</a> ARG=phi2 FILE=factor1.grid LABEL=factor1
<a href="https://plumed.github.io/doc-master/user-doc/html/_e_x_t_e_r_n_a_l.html">EXTERNAL</a> ARG=phi1 FILE=factor2.grid LABEL=factor2
<a href="https://plumed.github.io/doc-master/user-doc/html/_e_x_t_e_r_n_a_l.html">EXTERNAL</a> ARG=phi3 FILE=factor3.grid LABEL=factor3
<a href="https://plumed.github.io/doc-master/user-doc/html/_e_x_t_e_r_n_a_l.html">EXTERNAL</a> ARG=psi2 FILE=factor4.grid LABEL=factor4
<a href="https://plumed.github.io/doc-master/user-doc/html/_e_x_t_e_r_n_a_l.html">EXTERNAL</a> ARG=psi3 FILE=factor5.grid LABEL=factor5
<a href="https://plumed.github.io/doc-master/user-doc/html/_e_x_t_e_r_n_a_l.html">EXTERNAL</a> ARG=psi1 FILE=factor6.grid LABEL=factor6


<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ...
ARG=phi1,psi1,phi2,psi2,phi3,psi3,factor1.bias,factor2.bias,factor3.bias,factor4.bias,factor5.bias,factor6.bias
STRIDE=1
FILE=COLVAR
... <a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a>
</pre>{% endraw %}
