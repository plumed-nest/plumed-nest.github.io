**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
**Source:** meta_inputs/tetrapept_2D/plumed_biased.dat  
**Originally used with PLUMED version:** 2.7-mod  
**Stable:** [raw zipped stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [stderr](plumed_biased.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed_biased.dat.plumed_master.stdout.txt.zip) - [stderr](plumed_biased.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> LENGTH=A

t1: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=5,7,9,15
t2: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=7,9,15,17
t3: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=15,17,19,25
t4: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=17,19,25,27
t5: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=25,27,29,35
t6: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=27,29,35,37

<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=1-42
gyr: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_y_r_a_t_i_o_n.html">GYRATION</a> TYPE=RADIUS ATOMS=5,15,25,35,9,19,29,11,21,31,2,39,7,17,27,37,6,16,26,36

hy: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=8,18,28,38
ox: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=6,16,26,36
c1: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=ox GROUPB=hy  SWITCH={CUBIC D_0=3 D_MAX=4}

mt: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
PACE=500
ARG=gyr,c1
GRID_MIN=2.0,0.2 GRID_MAX=5,15 GRID_BIN=600,600
SIGMA=0.05,0.1  BIASFACTOR=5 HEIGHT=0.05
TEMP=300
...

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=t1,t2,t3,t4,t5,t6 FILE=dihedral STRIDE=500
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=mt.bias FILE=mt.gbias STRIDE=500
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=gyr,c1 FILE=colvar STRIDE=500

</pre>{% endraw %}
