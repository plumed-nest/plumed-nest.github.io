**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
**Source:** atlas_inputs/LJ-38/plumed_biased.dat  
**Originally used with PLUMED version:** 2.7-mod  
**Stable:** [raw zipped stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [stderr](plumed_biased.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed_biased.dat.plumed_master.stdout.txt.zip) - [stderr](plumed_biased.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> NATURAL
nsa: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIES=1-38 SWITCH={CUBIC D_0=1.25 D_MAX=1.5} 

n4: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=nsa FUNC=exp(-(x-4)*(x-4)/(2*0.5*0.5)) PERIODIC=NO
n5: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=nsa FUNC=exp(-(x-5)*(x-5)/(2*0.5*0.5)) PERIODIC=NO
n6: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=nsa FUNC=exp(-(x-6)*(x-6)/(2*0.5*0.5)) PERIODIC=NO
n7: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=nsa FUNC=exp(-(x-7)*(x-7)/(2*0.5*0.5)) PERIODIC=NO
n8: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=nsa FUNC=exp(-(x-8)*(x-8)/(2*0.5*0.5)) PERIODIC=NO
n9: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=nsa FUNC=exp(-(x-9)*(x-9)/(2*0.5*0.5)) PERIODIC=NO
n10: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=nsa FUNC=exp(-(x-10)*(x-10)/(2*0.5*0.5)) PERIODIC=NO
n11: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=nsa FUNC=exp(-(x-11)*(x-11)/(2*0.5*0.5)) PERIODIC=NO


at: <a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_l_a_s.html">ATLAS</a> ARG=n4,n5,n6,n7,n8,n9,n10,n11 REFERENCE=cluster_plumed.dat PACE=200 SIGMA=0.1 BIASFACTOR=5 HEIGHT=0.02  GRID_MAX=5.0 GRID_BIN=500 TEMP=0.12 TRUNCATE_GRIDS ADAPTIVE_WALL=1.0 STATIC_WALL=0.0 REGULARISE=1E-12

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=n4,n5,n6,n7,n8,n9,n10,n11 FMT=%8.4f FILE=colvar STRIDE=200
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=at_adaptive_wall FMT=%8.4f FILE=wall STRIDE=200
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=at FMT=%8.4f FILE=bias STRIDE=200
</pre>{% endraw %}
