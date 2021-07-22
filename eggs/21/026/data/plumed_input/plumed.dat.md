**Project ID:** [plumID:21.026]({{ '/' | absolute_url }}eggs/21/026/)  
**Source:** plumed_input/plumed.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a>  LENGTH=A  ENERGY=kcal/mol
<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=1-5946

dist: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1614,5843
dist2: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=2838,3207
dist3: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=473,5093
dist4: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=473,5843
<span style="color:blue">#between Lys(N+)374 and com of ASP21 ASP65</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=351,1038  LABEL=coo
dist5: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=5767,coo

path1: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_a_t_h_m_s_d.html">PATHMSD</a> REFERENCE=reference_path-renumb.pdb LAMBDA=1.46 NEIGH_STRIDE=100 NEIGH_SIZE=20


<a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
	ARG=path1.sss,path1.zzz PACE=400 HEIGHT=0.1 SIGMA=1,0.15 FILE=HILLS BIASFACTOR=50.0 TEMP=300.0 GRID_MIN=-10,-5 GRID_MAX=100,15 
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a>



<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=path1.zzz AT=9.0 KAPPA=100 EXP=2 EPS=1 LABEL=uwall

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> STRIDE=200 ARG=* FILE=COLVAR
</pre>{% endraw %}
