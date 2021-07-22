**Project ID:** [plumID:21.023]({{ '/' | absolute_url }}eggs/21/023/)  
**Source:** Data-mb/mb-wtm-bf3/plumed.dat  
**Originally used with PLUMED version:** 2.7  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="./MuellerBrown-Potential.dat.html">./MuellerBrown-Potential.dat</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
  LABEL=mtd

  ARG=p.x,p.y
  PACE=100
  SIGMA=0.1,0.1
  HEIGHT=1.5

  TEMP=1
 
  BIASFACTOR=3
  GRID_MIN=-5,-5
  GRID_MAX=5,5
  GRID_BIN=500,500
  CALC_RCT
  RCT_USTRIDE=1
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a>

w: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__m_e_t_a_d.html">REWEIGHT_METAD</a> TEMP=1

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=* FILE=colvar.data STRIDE=200
</pre>{% endraw %}
