**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
**Source:** hBromination/unbiased/plumed.dat  
**Originally used with PLUMED version:** 2.7  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue"># <a href="https://plumed.github.io/doc-master/user-doc/html/_vim_syntax.html">vim: ft=plumed</a></span>

<span style="color:blue">#UNITS</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> LENGTH=A

<span style="color:blue">#LOAD FILES</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_a_d.html">LOAD</a> FILE=../../code/Contacts.cpp

<span style="color:blue"># Atoms labels: [1-c1][2-c2][3-h1][4-h2][5-c5][6-h3][7-h4][8-h5][9-h6][10-b1][11-h7]</span>

<span style="color:blue"># Traditional distances </span>
d1:  <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=10,11 NOPBC
d2:  <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=11,1 NOPBC
d3:  <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=10,2 NOPBC
d4:  <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=11,2 NOPBC
d5:  <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=10,1 NOPBC

<span style="color:blue"># ========= walls definition =========</span>
<span style="color:blue"># prevent hydrogen molecules </span>
H: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=3,4,6,7,8,9,11
dHH: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e_s.html">DISTANCES</a> GROUPA=H GROUPB=H MIN={BETA=20} NOPBC
wallHH: <a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html">LOWER_WALLS</a> ARG=dHH.* AT=1.4 KAPPA=150.0 EXP=2 EPS=1.0 <span style="color:blue">#OFFSET=1.3</span>

<span style="color:blue"># keep COMs near</span>
uwall: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=d1,d2,d3,d4,d5 AT=3.0,3.0,3.0,3.0,3.0 KAPPA=150.0,150.0,150.0,150.0,150.0 

<span style="color:blue"># fix hydrogens on C1 -> bonding Br lateral</span>
d13: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1,3 NOPBC
d14: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1,4 NOPBC
wallCe1H1: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=d13,d14 AT=1.4,1.4 KAPPA=150.0,150.0 EXP=2,2 EPS=1.0,1.0 OFFSET=0.2,0.2

<span style="color:blue"># fix hydrogens on C3 -> nonbonding Br lateral</span>
d57: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=5,7 NOPBC
d58: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=5,8 NOPBC
d59: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=5,9 NOPBC
wallCe2H2: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=d57,d58,d59 AT=1.4,1.4,1.4 KAPPA=150.0,150.0,150.0 EXP=2,2,2 EPS=1.0,1.0,1.0 OFFSET=0.2,0.2,0.2

<span style="color:blue"># fix hydrogen on C2 -> bonding Br central</span>
d26: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=2,6 NOPBC
wallCmH1: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=d26 AT=1.4 KAPPA=150.0 EXP=2 EPS=1.0 OFFSET=0.2

<span style="color:blue"># ====== CONTACTS =======</span>
<span style="color:blue">#DEFINE GROUP OF ATOMS</span>
C: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=1,2,5
<span style="color:blue">#H: GROUP ATOMS=3,4,6,7,8,9,11</span>
Br: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=10

cc2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_t_a_c_t_s.html">CONTACTS</a> GROUPA=C SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8}
cb2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_t_a_c_t_s.html">CONTACTS</a> GROUPA=C GROUPB=Br SWITCH={RATIONAL D_0=0.0 R_0=1.9 NN=6 MM=8}
ch2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_t_a_c_t_s.html">CONTACTS</a> GROUPA=C GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.2 NN=6 MM=8}
bh2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_t_a_c_t_s.html">CONTACTS</a> GROUPA=Br GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.4 NN=6 MM=8}

<span style="color:blue"># ====== OUTPUT ======</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> STRIDE=50 FILE=distances ARG=d1,d2,d3,d4,d5
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> STRIDE=50 FILE=contacts ARG=cc2.*,cb2.*,ch2.*,bh2.*
</pre>{% endraw %}
