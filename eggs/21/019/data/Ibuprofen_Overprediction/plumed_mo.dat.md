**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
**Source:** Ibuprofen_Overprediction/plumed_mo.dat  
**Originally used with PLUMED version:** 2.5-mod  
**Stable:** [raw zipped stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [stderr](plumed_mo.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [stderr](plumed_mo.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue"># Define orientational vectors and angles</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ...
ATOMS1=6,10
ATOMS2=39,43
ATOMS3=72,76
ATOMS4=105,109
...
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s285_=9378_,9382.html">ATOMS285=9378,9382</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s286_=9411_,9415.html">ATOMS286=9411,9415</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s287_=9444_,9448.html">ATOMS287=9444,9448</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s288_=9477_,9481.html">ATOMS288=9477,9481</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_l_a_b_e_l_=_d_d__m_o1.html">LABEL=dd_mo1</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_p_o_n_e_n_t_s.html">COMPONENTS</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_._._..html">...</a> DISTA<a href="https://plumed.github.io/doc-master/user-doc/html/_._._..html">...</a>

vv_mo1: <a href="https://plumed.github.io/doc-master/user-doc/html/_n_o_r_m_a_l_i_z_e.html">NORMALIZE</a> ARG1=dd_mo1.x ARG2=dd_mo1.y ARG3=dd_mo1.z
dp_mat_mo1: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_o_t_p_r_o_d_u_c_t__m_a_t_r_i_x.html">DOTPRODUCT_MATRIX</a> GROUP1=vv_mo1.x GROUP2=vv_mo1.y GROUP3=vv_mo1.z
ang_mat_mo1: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG1=dp_mat_mo1 FUNC=acos(x) PERIODIC=NO

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ...
ATOMS1=18,20
ATOMS2=51,53
ATOMS3=84,86
ATOMS4=117,119
...
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s285_=9390_,9392.html">ATOMS285=9390,9392</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s286_=9423_,9425.html">ATOMS286=9423,9425</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s287_=9456_,9458.html">ATOMS287=9456,9458</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s288_=9489_,9491.html">ATOMS288=9489,9491</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_l_a_b_e_l_=_d_d__m_o2.html">LABEL=dd_mo2</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_p_o_n_e_n_t_s.html">COMPONENTS</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_._._..html">...</a> DISTA<a href="https://plumed.github.io/doc-master/user-doc/html/_._._..html">...</a>

vv_mo2: <a href="https://plumed.github.io/doc-master/user-doc/html/_n_o_r_m_a_l_i_z_e.html">NORMALIZE</a> ARG1=dd_mo2.x ARG2=dd_mo2.y ARG3=dd_mo2.z
dp_mat_mo2: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_o_t_p_r_o_d_u_c_t__m_a_t_r_i_x.html">DOTPRODUCT_MATRIX</a> GROUP1=vv_mo2.x GROUP2=vv_mo2.y GROUP3=vv_mo2.z
ang_mat_mo2: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG1=dp_mat_mo2 FUNC=acos(x) PERIODIC=NO

<span style="color:blue"># Plot Distribution</span>
valg_mo: <a href="https://plumed.github.io/doc-master/user-doc/html/_k_d_e.html">KDE</a> ARG1=ang_mat_mo1 ARG2=ang_mat_mo2  GRID_MIN=0.000,0.000 GRID_MAX=3.142,3.142 GRID_BIN=37,37 BANDWIDTH=0.250,0.250 KERNEL=GAUSSIAN
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=valg_mo FILE=plumed_md_mo.dat
</pre>{% endraw %}
