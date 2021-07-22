**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
**Source:** input/MacroD1_para_input/metad_35ang.dat  
**Originally used with PLUMED version:** 2.6  
**Stable:** [raw zipped stdout](metad_35ang.dat.plumed.stdout.txt.zip) - [stderr](metad_35ang.dat.plumed.stderr)  
**Master:** [raw zipped stdout](metad_35ang.dat.plumed_master.stdout.txt.zip) - [stderr](metad_35ang.dat.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=1-3740 ENTITY1=3741-3797

<span style="color:blue"># Group definition</span>
prot_noh: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> NDX_FILE=ref_index.ndx NDX_GROUP=Protein-H
ref: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> NDX_FILE=ref_index.ndx NDX_GROUP=Prot_ref_noH
AR6: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> NDX_FILE=ref_index.ndx NDX_GROUP=AR6_noH 

ref_center: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=ref
AR6_center: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=AR6

Fix: <a href="https://plumed.github.io/doc-master/user-doc/html/_f_i_x_e_d_a_t_o_m.html">FIXEDATOM</a> AT=5.0,5.0,5.0
Dis: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=ref_center,Fix

ref_coord: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_o_s_i_t_i_o_n.html">POSITION</a> ATOM=ref_center NOPBC
AR6_coord: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_o_s_i_t_i_o_n.html">POSITION</a> ATOM=AR6_center NOPBC

abs_x: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=AR6_coord.x,ref_coord.x FUNC=x-y PERIODIC=NO
abs_y: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=AR6_coord.y,ref_coord.y FUNC=x-y PERIODIC=NO
abs_z: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=AR6_coord.z,ref_coord.z FUNC=x-y PERIODIC=NO

rho: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=abs_x,abs_y,abs_z FUNC=sqrt(x*x+y*y+z*z) PERIODIC=NO
siga: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=abs_z,rho FUNC=sqrt(-x+y) PERIODIC=NO
theta: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=abs_x,abs_y FUNC=atan2(y,x) PERIODIC=-pi,pi

rmsd: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_m_s_d.html">RMSD</a> REFERENCE=ref_protein_noH_nosite.pdb TYPE=SIMPLE

<span style="color:blue"># Restraining potential of the sphere</span>
restr_dis: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=Dis AT=1.00 KAPPA=20000 OFFSET=0
restr_rho: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=rho AT=3.50 KAPPA=20000 OFFSET=0
restr_siga: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=siga AT=1.0 KAPPA=20000 OFFSET=0
restr_rmsd: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=rmsd AT=0.10 KAPPA=20000 OFFSET=0

<span style="color:blue"># Coordination number</span>
c: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=AR6 GROUPB=prot_noh R_0=0.45

<span style="color:blue"># Metadynamics</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
ARG=rho,siga,theta
GRID_MIN=0,0,-pi
GRID_MAX=3.6,1.2,pi
SIGMA=0.1,0.04,pi/8
HEIGHT=1.2
PACE=500
BIASFACTOR=20
TEMP=298
LABEL=metad
CALC_RCT
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=metad.* FILE=metad_data.dat STRIDE=5000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=restr_rho.*,restr_siga.*,restr_rmsd.* FILE=sphere_restraint.dat STRIDE=5000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=ref_coord.x,ref_coord.y,ref_coord.z FILE=ref_coord.dat STRIDE=5000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=AR6_coord.x,AR6_coord.y,AR6_coord.z FILE=AR6_coord.dat STRIDE=5000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=rho,siga,theta FILE=rtp_coord.dat STRIDE=5000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=c FILE=all_coordination_45.dat STRIDE=5000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=rmsd FILE=rmsd.dat STRIDE=5000
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=Dis FILE=distance.dat STRIDE=5000

<a href="https://plumed.github.io/doc-master/user-doc/html/_f_l_u_s_h.html">FLUSH</a> STRIDE=5000
</pre>{% endraw %}
