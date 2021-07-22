**Project ID:** [plumID:21.030]({{ '/' | absolute_url }}eggs/21/030/)  
**Source:** nspe/plumed.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#! <a href="https://plumed.github.io/doc-master/user-doc/html/_vim_syntax.html">vim:ft=plumed</a></span>

<span style="color:blue">#RESTART # read in ene from WTE equil </span>

ene: <a href="https://plumed.github.io/doc-master/user-doc/html/_e_n_e_r_g_y.html">ENERGY</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="cn.dat.html">cn.dat</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="cv.dat.html">cv.dat</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="ab.dat.html">ab.dat</a>

<span style="color:blue"># WTE</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
ARG=ene
PACE=5000 BIASFACTOR=60.0 HEIGHT=2.0
SIGMA=150
GRID_MIN=-500000 GRID_MAX=-100000
FILE=HILLS_ene
LABEL=wtemetad
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_b_m_e_t_a_d.html">PBMETAD</a> ...
  ARG=c,c1,c2,c3,c4,c5,c6,c7,c8,c9,c10,c11,c12,c13,c14,c15,c16,c17,c18,c19,c20,c21,c22,c23,c24,c25,c26,c27,c28,c29,c30,c31,c32,c33,c34,c35,c36,c37,c38,c39,c40,c41,c42,c43,c44,c45,c46,c47,c48,c49,c50,c51,c52,c53,c54,c55,c56,c57,c58,c59,c60,c61,c62,c63,c64,c65,c66,rg,alpha_d_plus,alpha_d_minus,alpha_plus,alpha_minus,c7beta_plus,c7beta_minus,alpha_d_plus_trans,alpha_d_minus_trans,alpha_plus_trans,alpha_minus_trans,c7beta_plus_trans,c7beta_minus_trans,omega0,omega1,omega2,omega3,omega4,omega5,omega6,omega7,omega8,omega9,omega10,phi0,phi1,phi2,phi3,phi4,phi5,phi6,phi7,phi8,phi9,phi10,psi0,psi1,psi2,psi3,psi4,psi5,psi6,psi7,psi8,psi9,psi10,psi11,chi0,chi1,chi2,chi3,chi4,chi5,chi6,chi7,chi8,chi9,chi10,chi11,chi20,chi21,chi22,chi23,chi24,chi25,chi26,chi27,chi28,chi29,chi210,chi211
  SIGMA=0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.5,0.1,1,1,1,1,1,1,1,1,1,1,1,1,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35,0.35
  HEIGHT=2.5 <span style="color:blue">#kj/mol</span>
  PACE=1000
  BIASFACTOR=140 <span style="color:blue">#baseBF x sqrt(NCV) ~ 100 (BF = ~12 for 10kcal/mol hill height cis/trans isom, CV=131)</span>
<span style="color:blue">#  TEMP=300</span>
  GRID_MIN=-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,0,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-1,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi,-pi
  GRID_MAX=40,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,20,3,50,50,50,50,50,50,50,50,50,50,50,50,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi,pi
  LABEL=pb
	FILE=HILLS_cn,HILLS_c1,HILLS_c2,HILLS_c3,HILLS_c4,HILLS_c5,HILLS_c6,HILLS_c7,HILLS_c8,HILLS_c9,HILLS_c10,HILLS_c11,HILLS_c12,HILLS_c13,HILLS_c14,HILLS_c15,HILLS_c16,HILLS_c17,HILLS_c18,HILLS_c19,HILLS_c20,HILLS_c21,HILLS_c22,HILLS_c23,HILLS_c24,HILLS_c25,HILLS_c26,HILLS_c27,HILLS_c28,HILLS_c29,HILLS_c30,HILLS_c31,HILLS_c32,HILLS_c33,HILLS_c34,HILLS_c35,HILLS_c36,HILLS_c37,HILLS_c38,HILLS_c39,HILLS_c40,HILLS_c41,HILLS_c42,HILLS_c43,HILLS_c44,HILLS_c45,HILLS_c46,HILLS_c47,HILLS_c48,HILLS_c49,HILLS_c50,HILLS_c51,HILLS_c52,HILLS_c53,HILLS_c54,HILLS_c55,HILLS_c56,HILLS_c57,HILLS_c58,HILLS_c59,HILLS_c60,HILLS_c61,HILLS_c62,HILLS_c63,HILLS_c64,HILLS_c65,HILLS_c66,HILLS_rg,HILLS_alpha_d_plus,HILLS_alpha_d_minus,HILLS_alpha_plus,HILLS_alpha_minus,HILLS_c7beta_plus,HILLS_c7beta_minus,HILLS_alpha_d_plus_trans,HILLS_alpha_d_minus_trans,HILLS_alpha_plus_trans,HILLS_alpha_minus_trans,HILLS_c7beta_plus_trans,HILLS_c7beta_minus_trans,HILLS_omega0,HILLS_omega1,HILLS_omega2,HILLS_omega3,HILLS_omega4,HILLS_omega5,HILLS_omega6,HILLS_omega7,HILLS_omega8,HILLS_omega9,HILLS_omega10,HILLS_phi0,HILLS_phi1,HILLS_phi2,HILLS_phi3,HILLS_phi4,HILLS_phi5,HILLS_phi6,HILLS_phi7,HILLS_phi8,HILLS_phi9,HILLS_phi10,HILLS_psi0,HILLS_psi1,HILLS_psi2,HILLS_psi3,HILLS_psi4,HILLS_psi5,HILLS_psi6,HILLS_psi7,HILLS_psi8,HILLS_psi9,HILLS_psi10,HILLS_psi11,HILLS_chi0,HILLS_chi1,HILLS_chi2,HILLS_chi3,HILLS_chi4,HILLS_chi5,HILLS_chi6,HILLS_chi7,HILLS_chi8,HILLS_chi9,HILLS_chi10,HILLS_chi11,HILLS_chi20,HILLS_chi21,HILLS_chi22,HILLS_chi23,HILLS_chi24,HILLS_chi25,HILLS_chi26,HILLS_chi27,HILLS_chi28,HILLS_chi29,HILLS_chi210,HILLS_chi211
... <a href="https://plumed.github.io/doc-master/user-doc/html/_p_b_m_e_t_a_d.html">PBMETAD</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=* STRIDE=250 FILE=COLVAR
</pre>{% endraw %}
