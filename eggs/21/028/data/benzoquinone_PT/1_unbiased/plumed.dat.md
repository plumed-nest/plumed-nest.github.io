**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
**Source:** benzoquinone_PT/1_unbiased/plumed.dat  
**Originally used with PLUMED version:** 2.7  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#! <a href="https://plumed.github.io/doc-master/user-doc/html/_vim_syntax.html">vim:ft=plumed</a></span>

<span style="color:blue"># input file for unbiased intramolecular double proton transfer in 2,5-diamino-1,4-benzoquinone </span>

<span style="color:blue"># we can use the coordination numbers of the heavy atoms!</span>
<span style="color:blue"># We take them of the type CC, CH, CO, CO, NH, OH</span>


<span style="color:blue">#UNITS</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> LENGTH=A

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


<span style="color:blue"># ==== PRINT STUFF ====</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> FILE=coordNumbers ARG=n1h,n2h,o1h,o2h,c1c,c1n,c1o,c1h,c2c,c2n,c2o,c2h,c3c,c3n,c3o,c3h,c4c,c4n,c4o,c4h,c5c,c5n,c5o,c5h,c6c,c6n,c6o,c6h STRIDE=50

</pre>{% endraw %}
