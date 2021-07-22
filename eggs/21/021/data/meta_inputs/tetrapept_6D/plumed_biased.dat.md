**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
**Source:** meta_inputs/tetrapept_6D/plumed_biased.dat  
**Originally used with PLUMED version:** 2.7-mod  
**Stable:** [raw zipped stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [stderr](plumed_biased.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed_biased.dat.plumed_master.stdout.txt.zip) - [stderr](plumed_biased.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#</span>
t1: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=5,7,9,15
t2: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=7,9,15,17
t3: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=15,17,19,25
t4: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=17,19,25,27
t5: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=25,27,29,35
t6: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=27,29,35,37

mt: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
PACE=500
ARG=t1,t2,t3,t4,t5,t6
SIGMA=0.2,0.2,0.2,0.2,0.2,0.2  BIASFACTOR=10 HEIGHT=2.0
TEMP=300
...

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=t1,t2,t3,t4,t5,t6 FILE=colvar STRIDE=500
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=mt.bias FILE=mt.gbias STRIDE=500
</pre>{% endraw %}
