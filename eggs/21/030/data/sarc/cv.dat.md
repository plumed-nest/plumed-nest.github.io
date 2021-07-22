**Project ID:** [plumID:21.030]({{ '/' | absolute_url }}eggs/21/030/)  
**Source:** sarc/cv.dat  
{% raw %}<pre>
<span style="color:blue">#! <a href="https://plumed.github.io/doc-master/user-doc/html/_vim_syntax.html">vim:ft=plumed</a></span>

<span style="color:blue"># rg</span>
rg: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_y_r_a_t_i_o_n.html">GYRATION</a> TYPE=RADIUS ATOMS=1,3,4,16,18,23,26,28,33,36,38,43,46,48,53,56,58,63,66,68,73,76,78,83,86,88,93,96,98,103,106,108,113,116,118

<a href="https://plumed.github.io/doc-master/user-doc/html/_a_l_p_h_a_b_e_t_a.html">ALPHABETA</a> ...
ATOMS1=4,3,1,23 REFERENCE=0 <span style="color:blue"># CA -NL - CLP - CA</span>
ATOMS2=23,18,16,33
ATOMS3=33,28,26,43
ATOMS4=43,38,36,53
ATOMS5=53,48,46,63
ATOMS6=63,58,56,73
ATOMS7=73,68,66,83
ATOMS8=83,78,76,93
ATOMS9=93,88,86,103
ATOMS10=103,98,96,113
ATOMS11=113,108,106,118
LABEL=ab_omega
... <a href="https://plumed.github.io/doc-master/user-doc/html/_a_l_p_h_a_b_e_t_a.html">ALPHABETA</a>

<span style="color:blue"># dihedrals </span>

<span style="color:blue"># phi CLP - CA - NL - CLP </span>
phi0: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=11,4,3,1
phi1: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=1,23,18,16
phi2: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=16,33,28,26
phi3: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=26,43,38,36
phi4: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=36,53,48,46
phi5: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=46,63,58,56
phi6: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=56,73,68,66
phi7: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=66,83,78,76
phi8: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=76,93,88,86
phi9: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=86,103,98,96
phi10: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=96,113,108,106

<span style="color:blue"># psi NL - CP2 - CA - NL</span>
psi0: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=13,11,4,3
psi1: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=3,1,23,18
psi2: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=18,16,33,28
psi3: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=28,26,43,38
psi4: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=38,36,53,48
psi5: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=48,46,63,58
psi6: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=58,56,73,68
psi7: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=68,66,83,78
psi8: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=78,76,93,88
psi9: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=88,86,103,98
psi10: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=98,96,113,108
psi11: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=108,106,118,116

<span style="color:blue"># omega CA - NL - CLP - CA</span>
omega0: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=4,3,1,23
omega1: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=23,18,16,33
omega2: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=33,28,26,43
omega3: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=43,38,36,53
omega4: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=53,48,46,63
omega5: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=63,58,56,73
omega6: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=73,68,66,83
omega7: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=83,78,76,93
omega8: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=93,88,86,103
omega9: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=103,98,96,113
omega10: <a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n.html">TORSION</a> ATOMS=113,108,106,118





</pre>{% endraw %}
