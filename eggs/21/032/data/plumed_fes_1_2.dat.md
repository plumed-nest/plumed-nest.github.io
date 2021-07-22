**Project ID:** [plumID:21.032]({{ '/' | absolute_url }}eggs/21/032/)  
**Source:** plumed_fes_1_2.dat  
**Originally used with PLUMED version:** 2.6  
**Stable:** [raw zipped stdout](plumed_fes_1_2.dat.plumed.stdout.txt.zip) - [stderr](plumed_fes_1_2.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed_fes_1_2.dat.plumed_master.stdout.txt.zip) - [stderr](plumed_fes_1_2.dat.plumed_master.stderr)  

{% raw %}<pre>

<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> LENGTH=A ENERGY=kcal/mol 
<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=1-781 STRIDE=1



metad:       <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_a_d.html">READ</a> FILE=COLVAR_REWEIGHT IGNORE_TIME VALUES=metad.bias
weights1: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__m_e_t_a_d.html">REWEIGHT_METAD</a>  TEMP=300 ARG=metad.bias


<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=67,88,243,292 LABEL=comCysZn69
<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=152,88,324,173 LABEL=comCysZn68
<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=211,292,359,173 LABEL=comCysZn67
<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=465,455,628,434 LABEL=comCysZn66
<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=512,554,465,761 LABEL=comCysZn65
<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=599,424,434,554 LABEL=comCysZn64
<a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=751,761,730,628 LABEL=comCysZn63



zn: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=775-781


Cys: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=67,88,243,292,152,324,173,211,359,465,455,628,434,512,554,761,599,424,751,730



zn69:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=781 GROUPB=comCysZn69 SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}
zn68:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=780 GROUPB=comCysZn68 SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}
zn67:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=779 GROUPB=comCysZn67 SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}
zn66:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=778 GROUPB=comCysZn66 SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}
zn65:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=777 GROUPB=comCysZn65 SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}
zn64:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=776 GROUPB=comCysZn64 SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}
zn63:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=775 GROUPB=comCysZn63 SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}



zn69_filterbbb: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=781 SPECIESB=comCysZn69 SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}
zn68_filterbbb: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=780 SPECIESB=comCysZn68  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}  
zn67_filterbbb: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=779 SPECIESB=comCysZn67  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24} 
zn66_filterbbb: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=778 SPECIESB=comCysZn66  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}
zn65_filterbbb: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=777 SPECIESB=comCysZn65  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}
zn64_filterbbb: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=776 SPECIESB=comCysZn64  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}
zn63_filterbbb: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=775 SPECIESB=comCysZn63  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24} 


zn69_filter:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=781 SPECIESB=comCysZn69  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}   MEAN MORE_THAN={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24}  
zn68_filter:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=780 SPECIESB=comCysZn68  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}    MEAN MORE_THAN={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24}  
zn67_filter:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=779 SPECIESB=comCysZn67  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}    MEAN MORE_THAN={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24}  
zn66_filter:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=778 SPECIESB=comCysZn66  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}   MEAN MORE_THAN={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24}  
zn65_filter:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=777 SPECIESB=comCysZn65 SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}     MEAN MORE_THAN={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24} 
zn64_filter:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=776 SPECIESB=comCysZn64  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}    MEAN MORE_THAN={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24} 
zn63_filter:    <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n_n_u_m_b_e_r.html">COORDINATIONNUMBER</a> SPECIESA=775 SPECIESB=comCysZn63  SWITCH={RATIONAL R_0=2.9 D_MAX=5 NN=12 MM=24}    MEAN MORE_THAN={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24} 



<a href="https://plumed.github.io/doc-master/user-doc/html/_m_f_i_l_t_e_r__m_o_r_e.html">MFILTER_MORE</a> DATA=zn69_filterbbb SWITCH={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24}  LOWMEM LABEL=d69  HIGHEST 
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_f_i_l_t_e_r__m_o_r_e.html">MFILTER_MORE</a> DATA=zn68_filterbbb SWITCH={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24}   LOWMEM LABEL=d68 HIGHEST  
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_f_i_l_t_e_r__m_o_r_e.html">MFILTER_MORE</a> DATA=zn67_filterbbb SWITCH={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24}   LOWMEM LABEL=d67 HIGHEST 
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_f_i_l_t_e_r__m_o_r_e.html">MFILTER_MORE</a> DATA=zn66_filterbbb SWITCH={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24}   LOWMEM LABEL=d66 HIGHEST  
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_f_i_l_t_e_r__m_o_r_e.html">MFILTER_MORE</a> DATA=zn65_filterbbb SWITCH={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24}   LOWMEM LABEL=d65 HIGHEST  
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_f_i_l_t_e_r__m_o_r_e.html">MFILTER_MORE</a> DATA=zn64_filterbbb SWITCH={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24}  LOWMEM LABEL=d64 HIGHEST 
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_f_i_l_t_e_r__m_o_r_e.html">MFILTER_MORE</a> DATA=zn63_filterbbb SWITCH={RATIONAL R_0=3.2 D_MAX=5 NN=12 MM=24}   LOWMEM LABEL=d63 HIGHEST  



Cyss2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> ARG=d69.highest,d68.highest,d67.highest,d66.highest,d65.highest,d64.highest,d63.highest   PERIODIC=NO


m: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> ARG=zn69_filter.morethan,zn68_filter.morethan,zn67_filter.morethan,zn66_filter.morethan,zn65_filter.morethan,zn64_filter.morethan,zn63_filter.morethan   PERIODIC=NO

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_r_m_s_d.html">DRMSD</a> REFERENCE=reference.pdb LOWER_CUTOFF=0.1 UPPER_CUTOFF=8 LABEL=<a href="https://plumed.github.io/doc-master/user-doc/html/_d_r_m_s_d.html">DRMSD</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
   ARG=Cyss2,m
   GRID_MIN=0,0
   GRID_MAX=30,10
   BANDWIDTH=0.4,0.4
   GRID_BIN=300,300
   LOGWEIGHTS=weights1
   LABEL=hB6
   NORMALIZATION=false
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>


<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
   ARG=m,DRMSD
   GRID_MIN=0,0
   GRID_MAX=9,12
   GRID_BIN=300,300
   BANDWIDTH=0.5,0.5
   LOGWEIGHTS=weights1
   LABEL=hB5
   NORMALIZATION=false
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>


fes6: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hB6 TEMP=300
fes5: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hB5 TEMP=300

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hB6 FILE=histo6.dat FMT=%8.4f
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hB5 FILE=histo5.dat FMT=%8.4f
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=fes6 FILE=fes6.dat FMT=%8.4f
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=fes5 FILE=fes5.dat FMT=%8.4f




</pre>{% endraw %}
