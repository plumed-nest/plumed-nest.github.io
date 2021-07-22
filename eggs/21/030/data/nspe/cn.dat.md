**Project ID:** [plumID:21.030]({{ '/' | absolute_url }}eggs/21/030/)  
**Source:** nspe/cn.dat  
{% raw %}<pre>
<span style="color:blue">#! <a href="https://plumed.github.io/doc-master/user-doc/html/_vim_syntax.html">vim:ft=plumed</a></span>


<span style="color:blue"># coordination </span>
r1: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=13,22 <span style="color:blue">#res 1 and 10 agg in trial 1</span>
r2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=41,50
r3: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=64,73
r4: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=87,96
r5: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=110,119
r6: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=133,142 <span style="color:blue">#res 6 and 9 should be coordinated in a helix</span>
r7: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=156,165
r8: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=179,188
r9: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=202,211 <span style="color:blue">#CG-CH </span>
r10: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=225,234
r11: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=248,257
r12: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=270,279

<span style="color:blue">#distances (12*11)/2 = 66 pairs?</span>
d1-2: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r1,r2
d1-3: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r1,r3
d1-4: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r1,r4
d1-5: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r1,r5
d1-6: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r1,r6
d1-7: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r1,r7
d1-8: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r1,r8
d1-9: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r1,r9
d1-10: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r1,r10
d1-11: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r1,r11
d1-12: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r1,r12
d2-3: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r2,r3
d2-4: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r2,r4
d2-5: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r2,r5
d2-6: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r2,r6
d2-7: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r2,r7
d2-8: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r2,r8
d2-9: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r2,r9
d2-10: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r2,r10
d2-11: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r2,r11
d2-12: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r2,r12
d3-4: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r3,r4
d3-5: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r3,r5
d3-6: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r3,r6
d3-7: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r3,r7
d3-8: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r3,r8
d3-9: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r3,r9
d3-10: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r3,r10
d3-11: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r3,r11
d3-12: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r3,r12
d4-5: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r4,r5
d4-6: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r4,r6
d4-7: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r4,r7
d4-8: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r4,r8
d4-9: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r4,r9
d4-10: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r4,r10
d4-11: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r4,r11
d4-12: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r4,r12
d5-6: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r5,r6
d5-7: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r5,r7
d5-8: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r5,r8
d5-9: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r5,r9
d5-10: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r5,r10
d5-11: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r5,r11
d5-12: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r5,r12
d6-7: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r6,r7
d6-8: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r6,r8
d6-9: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r6,r9
d6-10: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r6,r10
d6-11: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r6,r11
d6-12: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r6,r12
d7-8: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r7,r8
d7-9: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r7,r9
d7-10: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r7,r10
d7-11: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r7,r11
d7-12: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r7,r12
d8-9: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r8,r9
d8-10: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r8,r10
d8-11: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r8,r11
d8-12: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r8,r12
d9-10: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r9,r10
d9-11: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r9,r11
d9-12: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r9,r12
d10-11: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r10,r11
d10-12: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r10,r12
d11-12: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=r11,r12

<span style="color:blue"># coordination</span>
c: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1,r1,r1,r1,r1,r1,r1,r1,r1,r1,r1,r2,r2,r2,r2,r2,r2,r2,r2,r2,r2,r3,r3,r3,r3,r3,r3,r3,r3,r3,r4,r4,r4,r4,r4,r4,r4,r4,r5,r5,r5,r5,r5,r5,r5,r6,r6,r6,r6,r6,r6,r7,r7,r7,r7,r7,r8,r8,r8,r8,r9,r9,r9,r10,r10,r11  GROUPB=r2,r3,r4,r5,r6,r7,r8,r9,r10,r11,r12,r3,r4,r5,r6,r7,r8,r9,r10,r11,r12,r4,r5,r6,r7,r8,r9,r10,r11,r12,r5,r6,r7,r8,r9,r10,r11,r12,r6,r7,r8,r9,r10,r11,r12,r7,r8,r9,r10,r11,r12,r8,r9,r10,r11,r12,r9,r10,r11,r12,r10,r11,r12,r11,r12,r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 PAIR

<span style="color:blue"># each ring coord</span>
c1: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1 GROUPB=r2 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1 GROUPB=r3 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c3: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1 GROUPB=r4 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c4: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1 GROUPB=r5 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c5: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1 GROUPB=r6 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c6: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1 GROUPB=r7 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c7: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1 GROUPB=r8 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c8: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1 GROUPB=r9 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c9: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1 GROUPB=r10 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c10: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1 GROUPB=r11 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c11: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r1 GROUPB=r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c12: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r2 GROUPB=r3 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c13: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r2 GROUPB=r4 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c14: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r2 GROUPB=r5 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c15: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r2 GROUPB=r6 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c16: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r2 GROUPB=r7 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c17: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r2 GROUPB=r8 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c18: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r2 GROUPB=r9 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c19: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r2 GROUPB=r10 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c20: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r2 GROUPB=r11 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10 
c21: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r2 GROUPB=r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c22: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r3 GROUPB=r4 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c23: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r3 GROUPB=r5 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c24: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r3 GROUPB=r6 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c25: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r3 GROUPB=r7 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c26: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r3 GROUPB=r8 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c27: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r3 GROUPB=r9 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c28: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r3 GROUPB=r10 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c29: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r3 GROUPB=r11 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c30: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r3 GROUPB=r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c31: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r4 GROUPB=r5 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c32: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r4 GROUPB=r6 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c33: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r4 GROUPB=r7 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c34: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r4 GROUPB=r8 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c35: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r4 GROUPB=r9 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c36: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r4 GROUPB=r10 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c37: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r4 GROUPB=r11 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c38: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r4 GROUPB=r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c39: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r5 GROUPB=r6 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c40: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r5 GROUPB=r7 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c41: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r5 GROUPB=r8 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c42: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r5 GROUPB=r9 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c43: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r5 GROUPB=r10 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c44: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r5 GROUPB=r11 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c45: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r5 GROUPB=r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c46: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r6 GROUPB=r7 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c47: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r6 GROUPB=r8 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c48: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r6 GROUPB=r9 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c49: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r6 GROUPB=r10 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c50: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r6 GROUPB=r11 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c51: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r6 GROUPB=r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c52: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r7 GROUPB=r8 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c53: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r7 GROUPB=r9 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c54: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r7 GROUPB=r10 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c55: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r7 GROUPB=r11 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c56: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r7 GROUPB=r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c57: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r8 GROUPB=r9 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c58: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r8 GROUPB=r10 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c59: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r8 GROUPB=r11 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c60: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r8 GROUPB=r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c61: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r9 GROUPB=r10 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c62: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r9 GROUPB=r11 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c63: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r9 GROUPB=r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c64: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r10 GROUPB=r11 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c65: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r10 GROUPB=r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10
c66: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_o_r_d_i_n_a_t_i_o_n.html">COORDINATION</a> GROUPA=r11 GROUPB=r12 R_0=0.5 NN=8 MM=12  NLIST NL_CUTOFF=0.75 NL_STRIDE=10

</pre>{% endraw %}
