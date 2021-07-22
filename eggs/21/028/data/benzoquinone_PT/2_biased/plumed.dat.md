**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
**Source:** benzoquinone_PT/2_biased/plumed.dat  
**Originally used with PLUMED version:** 2.7  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#! <a href="https://plumed.github.io/doc-master/user-doc/html/_vim_syntax.html">vim:ft=plumed</a></span>

<span style="color:blue"># input file for biased intramolecular double proton transfer in 2,5-diamino-1,4-benzoquinone with Deep-TDA</span>

<span style="color:blue"># we can use the coordination numbero of the heavy atoms!</span>
<span style="color:blue"># we would like to preserve the symmetries</span>

<span style="color:blue">#UNITS</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> LENGTH=A

<a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_a_d.html">LOAD</a> FILE=../../code/PytorchModel.cpp

<span style="color:blue"># ==== GROUPS ====</span>
C: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=1,2,3,4,5,6
N: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=9,12
O: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=15,16
H: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=7,8,10,11,13,14

<span style="color:blue"># ==== HEAVY ATOMS ====</span>
C1: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=1
C2: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=2
C3: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=3
C4: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=4
C5: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=5
C6: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=6
N1: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=9
N2: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=12
O1: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=15
O2: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=16

c1c: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C1 GROUPB=C SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c1n: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C1 GROUPB=N SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c1o: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C1 GROUPB=O SWITCH={RATIONAL D_0=0.0 R_0=1.6 NN=6 MM=8} NOPBC
c1h: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C1 GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.2 NN=6 MM=8} NOPBC
c2c: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C2 GROUPB=C SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c2n: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C2 GROUPB=N SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c2o: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C2 GROUPB=O SWITCH={RATIONAL D_0=0.0 R_0=1.6 NN=6 MM=8} NOPBC
c2h: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C2 GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.2 NN=6 MM=8} NOPBC
c3c: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C3 GROUPB=C SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c3n: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C3 GROUPB=N SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c3o: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C3 GROUPB=O SWITCH={RATIONAL D_0=0.0 R_0=1.6 NN=6 MM=8} NOPBC
c3h: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C3 GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.2 NN=6 MM=8} NOPBC
c4c: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C4 GROUPB=C SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c4n: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C4 GROUPB=N SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c4o: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C4 GROUPB=O SWITCH={RATIONAL D_0=0.0 R_0=1.6 NN=6 MM=8} NOPBC
c4h: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C4 GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.2 NN=6 MM=8} NOPBC
c5c: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C5 GROUPB=C SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c5n: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C5 GROUPB=N SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c5o: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C5 GROUPB=O SWITCH={RATIONAL D_0=0.0 R_0=1.6 NN=6 MM=8} NOPBC
c5h: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C5 GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.2 NN=6 MM=8} NOPBC
c6c: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C6 GROUPB=C SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c6n: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C6 GROUPB=N SWITCH={RATIONAL D_0=0.0 R_0=1.7 NN=6 MM=8} NOPBC
c6o: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C6 GROUPB=O SWITCH={RATIONAL D_0=0.0 R_0=1.6 NN=6 MM=8} NOPBC
c6h: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=C6 GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.2 NN=6 MM=8} NOPBC

n1h: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=N1 GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.1 NN=6 MM=8} NOPBC
n2h: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=N2 GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.1 NN=6 MM=8} NOPBC

o1h: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=O1 GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.2 NN=6 MM=8} NOPBC
o2h: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=O2 GROUPB=H SWITCH={RATIONAL D_0=0.0 R_0=1.2 NN=6 MM=8} NOPBC

<span style="color:blue"># ==== PYTORCH MODEL ====</span>
nncv: <a href="https://plumed.github.io/doc-master/user-doc/html/_p_y_t_o_r_c_h__m_o_d_e_l.html">PYTORCH_MODEL</a> MODEL=../deepTDA_benzo.pt ARG=n1h,n2h,o1h,o2h,c1c,c1n,c1o,c1h,c2c,c2n,c2o,c2h,c3c,c3n,c3o,c3h,c4c,c4n,c4o,c4h,c5c,c5n,c5o,c5h,c6c,c6n,c6o,c6h

<span style="color:blue"># ==== LIMIT CV ====</span>
lwall_nncv: <a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html">LOWER_WALLS</a> ARG=nncv.node-0 AT=-16 KAPPA=400
uwall_nncv: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=nncv.node-0 AT=+16 KAPPA=400

<span style="color:blue"># ==== OPES PARAMETERS ====</span>
opes: <a href="https://plumed.github.io/doc-master/user-doc/html/_o_p_e_s__m_e_t_a_d.html">OPES_METAD</a> ...
        ARG=nncv.node-0
        PACE=500
        BARRIER=120
        SIGMA=0.20
        TEMP=300
...

<span style="color:blue"># ==== PRINT STUFF ====</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> FILE=colvar ARG=nncv.node-0,opes.*,n1h,n2h,o1h,o2h,lwall_nncv.*,uwall_nncv.* STRIDE=500

</pre>{% endraw %}
