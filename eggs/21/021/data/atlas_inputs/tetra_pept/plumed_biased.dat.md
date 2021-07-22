**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
**Source:** atlas_inputs/tetra_pept/plumed_biased.dat  
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


at: <a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_l_a_s.html">ATLAS</a> ...
REFERENCE=cluster_plumed.dat PACE=500
ARG=t1,t2,t3,t4,t5,t6
SIGMA=0.1  BIASFACTOR=10 HEIGHT=2.0
GRID_MAX=3.5 GRID_BIN=500 TEMP=300 TRUNCATE_GRIDS
REGULARISE=1E-12
STATIC_WALL=0.00
ADAPTIVE_WALL=1.00
...


<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=t1,t2,t3,t4,t5,t6 FILE=colvar STRIDE=500
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=at,at_wtfact FILE=at.gbias STRIDE=500
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=at_adaptive_wall FILE=wall STRIDE=500
</pre>{% endraw %}
