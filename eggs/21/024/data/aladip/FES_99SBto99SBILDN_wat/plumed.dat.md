**Project ID:** [plumID:21.024]({{ '/' | absolute_url }}eggs/21/024/)  
**Source:** aladip/FES_99SBto99SBILDN_wat/plumed.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue"># set up two variables for Phi and Psi dihedral angles</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> STRIDE=1 ENTITY0=1-22

phi: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=5,7,9,15
psi: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=7,9,15,17

pm: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_o_p_e_r_t_y_m_a_p.html">PROPERTYMAP</a> REFERENCE=reference.pdb PROPERTY=X LAMBDA=1000
bvX: <a href="https://plumed.github.io/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html">BIASVALUE</a> ARG=pm.X

<a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
LABEL=metad
ARG=phi,psi
PACE=500 
HEIGHT=1.2 
SIGMA=0.35,0.35 
FILE=HILLS 
BIASFACTOR=6.0
GRID_MIN=-pi,-pi
GRID_MAX=pi,pi 
TEMP=300.0
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a>

<span style="color:blue"># monitor the two variables and the metadynamics bias potential</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> STRIDE=100 ARG=phi,psi,pm.X,metad.bias,bvX.pm.X_bias FILE=COLVAR
</pre>{% endraw %}
