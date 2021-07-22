**Project ID:** [plumID:21.030]({{ '/' | absolute_url }}eggs/21/030/)  
**Source:** sarc/plumed.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#! <a href="https://plumed.github.io/doc-master/user-doc/html/_vim_syntax.html">vim:ft=plumed</a></span>

<span style="color:blue">#RESTART # read in ene from WTE equil </span>

ene: <a href="https://plumed.github.io/doc-master/user-doc/html/_e_n_e_r_g_y.html">ENERGY</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="ab.dat.html">ab.dat</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="cv.dat.html">cv.dat</a>

<span style="color:blue"># WTE</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
ARG=ene
PACE=5000 BIASFACTOR=60.0 HEIGHT=2.0
SIGMA=150
GRID_MIN=-400000 GRID_MAX=-200000
FILE=HILLS_ene
LABEL=wtemetad
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_b_m_e_t_a_d.html">PBMETAD</a> ...
   ARG=rg,alpha_d_plus,alpha_d_minus,alpha_plus,alpha_minus,c7beta_plus,c7beta_minus,alpha_d_plus_trans,alpha_d_minus_trans,alpha_plus_trans,alpha_minus_trans,c7beta_plus_trans,c7beta_minus_trans,omega0,omega1,omega2,omega3,omega4,omega5,omega6,omega7,omega8,omega9,omega10,phi0,phi1,phi2,phi3,phi4,phi5,phi6,phi7,phi8,phi9,phi10,psi0,psi1,psi2,psi3,psi4,psi5,psi6,psi7,psi8,psi9,psi10,psi11
  SIGMA=0.1,1,1,1,1,1,1,1,1,1,1,1,1,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35
	HEIGHT=2.5 <span style="color:blue">#kj/mol</span>
  PACE=1000
  BIASFACTOR=75 <span style="color:blue">#max rule baseBF x sqrt(NCV) ~ 100 (BF = ~12 for 10kcal/mol hill height cis/trans isom, CV=131)</span>
  GRID_MIN=0,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi
  GRID_MAX=3,50,50,50,50,50,50,50,50,50,50,50,50,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi
  LABEL=pb
	FILE=HILLS_rg,HILLS_alpha_d_plus,HILLS_alpha_d_minus,HILLS_alpha_plus,HILLS_alpha_minus,HILLS_c7beta_plus,HILLS_c7beta_minus,HILLS_alpha_d_plus_trans,HILLS_alpha_d_minus_trans,HILLS_alpha_plus_trans,HILLS_alpha_minus_trans,HILLS_c7beta_plus_trans,HILLS_c7beta_minus_trans,HILLS_omega0,HILLS_omega1,HILLS_omega2,HILLS_omega3,HILLS_omega4,HILLS_omega5,HILLS_omega6,HILLS_omega7,HILLS_omega8,HILLS_omega9,HILLS_omega10,HILLS_phi0,HILLS_phi1,HILLS_phi2,HILLS_phi3,HILLS_phi4,HILLS_phi5,HILLS_phi6,HILLS_phi7,HILLS_phi8,HILLS_phi9,HILLS_phi10,HILLS_psi0,HILLS_psi1,HILLS_psi2,HILLS_psi3,HILLS_psi4,HILLS_psi5,HILLS_psi6,HILLS_psi7,HILLS_psi8,HILLS_psi9,HILLS_psi10,HILLS_psi11
... <a href="https://plumed.github.io/doc-master/user-doc/html/_p_b_m_e_t_a_d.html">PBMETAD</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=* STRIDE=250 FILE=COLVAR
</pre>{% endraw %}
