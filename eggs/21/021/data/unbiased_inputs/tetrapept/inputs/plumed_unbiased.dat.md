**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
**Source:** unbiased_inputs/tetrapept/inputs/plumed_unbiased.dat  
**Originally used with PLUMED version:** 2.7-mod  
**Stable:** [raw zipped stdout](plumed_unbiased.dat.plumed.stdout.txt.zip) - [stderr](plumed_unbiased.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed_unbiased.dat.plumed_master.stdout.txt.zip) - [stderr](plumed_unbiased.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#</span>
t1: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=5,7,9,15
t2: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=7,9,15,17
t3: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=15,17,19,25
t4: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=17,19,25,27
t5: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=25,27,29,35
t6: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=27,29,35,37

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=t1,t2,t3,t4,t5,t6 FILE=colvar STRIDE=1
</pre>{% endraw %}
