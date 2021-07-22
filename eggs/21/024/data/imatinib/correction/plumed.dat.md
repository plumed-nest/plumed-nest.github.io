**Project ID:** [plumID:21.024]({{ '/' | absolute_url }}eggs/21/024/)  
**Source:** imatinib/correction/plumed.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=1-68
pm: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_o_p_e_r_t_y_m_a_p.html">PROPERTYMAP</a> REFERENCE=reference.pdb PROPERTY=X LAMBDA=500
bvX: <a href="https://plumed.github.io/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html">BIASVALUE</a> ARG=pm.X
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=bvX.pm.X_bias STRIDE=500 FILE=BIAS
</pre>{% endraw %}
