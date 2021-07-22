**Project ID:** [plumID:21.032]({{ '/' | absolute_url }}eggs/21/032/)  
**Source:** plumed_PB_WTMetad.dat  
**Originally used with PLUMED version:** 2.6  
**Stable:** [raw zipped stdout](plumed_PB_WTMetad.dat.plumed.stdout.txt.zip) - [stderr](plumed_PB_WTMetad.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed_PB_WTMetad.dat.plumed_master.stdout.txt.zip) - [stderr](plumed_PB_WTMetad.dat.plumed_master.stderr)  

{% raw %}<pre>

<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> LENGTH=A ENERGY=kcal/mol 
<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=1-774 STRIDE=1


<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=67,88,243,292 LABEL=comCysZn69

<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=152,88,324,173 LABEL=comCysZn68
<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=211,292,359,173 LABEL=comCysZn67
<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=465,455,628,434 LABEL=comCysZn66
<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=512,554,465,761 LABEL=comCysZn65
<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=599,424,434,554 LABEL=comCysZn64
<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=751,761,730,628 LABEL=comCysZn63



zn69:  <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=781 GROUPB=comCysZn69 R_0=3.5  NLIST NL_CUTOFF=8 NL_STRIDE=100
zn68:  <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=780 GROUPB=comCysZn68 R_0=3.5 NLIST NL_CUTOFF=8 NL_STRIDE=100 
zn67:  <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=779 GROUPB=comCysZn67 R_0=3.5 NLIST NL_CUTOFF=8 NL_STRIDE=100 
zn66:  <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=778  GROUPB=comCysZn66 R_0=3.5 NLIST NL_CUTOFF=8 NL_STRIDE=100 
zn65:  <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=777 GROUPB=comCysZn65 R_0=3.5 NLIST NL_CUTOFF=8 NL_STRIDE=100 
zn64:  <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=776 GROUPB=comCysZn64 R_0=3.5 NLIST NL_CUTOFF=8 NL_STRIDE=100 
zn63:  <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=775  GROUPB=comCysZn63 R_0=3.5 NLIST NL_CUTOFF=8 NL_STRIDE=100  


<a href="https://plumed.github.io/doc-master/user-doc/html/_p_b_m_e_t_a_d.html">PBMETAD</a> ...
ARG=zn69,zn68,zn67,zn66,zn65,zn64,zn63
PACE=500 BIASFACTOR=18.0 HEIGHT=0.6 TEMP=300.0
INTERVAL_MIN=0.4,0.4,0.4,0.4,0.4,0.4,0.4
INTERVAL_MAX=4,4,4,4,4,4,4
SIGMA=0.15,0.15,0.15,0.15,0.15,0.15,0.15
GRID_MIN=0,0,0,0,0,0,0
GRID_MAX=30,30,30,30,30,30,30
WALKERS_MPI
FILE=HILLS_69,HILLS_68,HILLS_67,HILLS_66,HILLS_65,HILLS_64,HILLS_63 LABEL=metad
... <a href="https://plumed.github.io/doc-master/user-doc/html/_p_b_m_e_t_a_d.html">PBMETAD</a>



</pre>{% endraw %}
