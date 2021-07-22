**Project ID:** [plumID:21.027]({{ '/' | absolute_url }}eggs/21/027/)  
**Source:** D770-N771insNPG/plumed.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_l_i_n_f_o.html">MOLINFO</a> STRUCTURE=NPGins_active.pdb 
<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=1-4752
<span style="color:blue"># Distances describing the two saltbridges K745(NZ):E762(CD) and K745(ΝΖ):D855(CG)</span>
<span style="color:blue"># that reflect the conformation of the aC helix</span>
<span style="color:blue"># (CVs described in Ludo's paper doi:10.1073/pnas.1221953110)</span>
K745_E762: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=745,1016
K745_D855: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=745,2556

<span style="color:blue"># Distance between the two distance</span>
<span style="color:blue"># When both saltbridges are formed, the distance between the two distances (CV)</span>
<span style="color:blue"># is close to 0. This CV is able to characterise the displacement of the fuctionally important</span>
<span style="color:blue"># E762 located in the aC helix of the N-lobe in its transition from the so-called "aC-in" to "aC-out" conformation</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ...
    LABEL=d
    ARG=K745_E762,K745_D855
    VAR=a,b
    FUNC=a-b
    PERIODIC=NO
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a>

<span style="color:blue"># Distance from active cmap</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="cmap_active.dat.html">cmap_active.dat</a>

<span style="color:blue"># Distance form inactive cmap</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="cmap_inactive.dat.html">cmap_inactive.dat</a>

<span style="color:blue"># Monitor the helical content of the aC-helix to probe </span>
<span style="color:blue"># its intrisically disordered nature in the monomeric form</span>
armsd: <a href="https://plumed.github.io/doc-master/user-doc/html/_a_l_p_h_a_r_m_s_d.html">ALPHARMSD</a> RESIDUES=751-773 TYPE=DRMSD R_0=0.08 D_0=0.0 NN=8 MM=12

</pre>{% endraw %}
