**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
**Source:** meta_inputs/LJ-38/plumed.dat  
**Originally used with PLUMED version:** 2.7-mod  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> NATURAL
nsa: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIES=1-38 SWITCH={CUBIC D_0=1.25 D_MAX=1.5} <span style="color:blue">#MORE_THAN={GAUSSIAN R_0=0.5 D_0=6}</span>

ns: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=nsa FUNC=exp(-(x-6)*(x-6)/(2*0.5*0.5)) PERIODIC=NO
ne: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=nsa FUNC=exp(-(x-8)*(x-8)/(2*0.5*0.5)) PERIODIC=NO

mt: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
ARG=ns,ne 
PACE=500 
SIGMA=0.1,0.1 
BIASFACTOR=10 HEIGHT=1.0 TEMP=0.12 
GRID_MIN=0.,0. GRID_MAX=28,20 GRID_BIN=300,300
...

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=ns,ne,mt.bias FMT=%8.4f FILE=colvar STRIDE=500
</pre>{% endraw %}
