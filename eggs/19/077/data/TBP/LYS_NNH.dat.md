**Project ID:** [plumID:19.077]({{ '/' | absolute_url }}eggs/19/077/)  
**Source:** TBP/LYS_NNH.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [raw zipped stdout](LYS_NNH.dat.plumed.stdout.txt.zip) - [stderr](LYS_NNH.dat.plumed.stderr)  
**Master:** [raw zipped stdout](LYS_NNH.dat.plumed_master.stdout.txt.zip) - [stderr](LYS_NNH.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#RESTART</span>
<span style="color:blue">#CVs </span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_l_i_n_f_o.html">MOLINFO</a> MOLTYPE=protein STRUCTURE=lys.pdb
c1: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=1-34 <span style="color:blue">#COM from peptide to surface </span>
d1: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1945,c1 COMPONENTS NOPBC <span style="color:blue">#dist peptide to surface</span>

<span style="color:blue">#restraint </span>
wall1: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=d1.z AT=3.0 KAPPA=1500

<span style="color:blue">#pb</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
ARG=d1.z
SIGMA=0.05
HEIGHT=0.2 <span style="color:blue">#kj/mol</span>
PACE=500 
BIASFACTOR=10
TEMP=300
GRID_MIN=-3.0
GRID_MAX=7.0
LABEL=metad
FILE=HILLS.d1
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a>


<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=d1.z,metad.bias STRIDE=500 FILE=COLVAR

</pre>{% endraw %}
