**Project ID:** [plumID:19.003]({{ '/' | absolute_url }}eggs/19/003/)  
**Source:** EMMI-ClpP/PRODUCTION/plumed.dat  
**Originally used with PLUMED version:** 2.6-dev  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue"># read reference pdb file</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_l_i_n_f_o.html">MOLINFO</a> STRUCTURE=ClpP_structure.pdb

<span style="color:blue"># define heavy atoms group</span>
Protein-H: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> NDX_FILE=index.ndx NDX_GROUP=Protein-H

<span style="color:blue"># create emmi score</span>
emmi: <a href="https://plumed.github.io/doc-master/user-doc/html/_e_m_m_i.html">EMMI</a> NOPBC SIGMA_MIN=0.03 TEMP=300.0 NL_STRIDE=100 NL_CUTOFF=0.01 NOISETYPE=MARGINAL RESOLUTION=0.1 GMM_FILE=ClpP_GMM.dat ATOMS=Protein-H

<span style="color:blue"># add as bias </span>
emr: <a href="https://plumed.github.io/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html">BIASVALUE</a> ARG=emmi.scoreb STRIDE=4

<span style="color:blue"># print useful stuff</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=emr.* FILE=COLVAR STRIDE=200 FMT=%30.10f
</pre>{% endraw %}
