**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
**Source:** Ibuprofen_Overprediction/plumed_tor.dat  
**Originally used with PLUMED version:** 2.5-mod  
**Stable:** [raw zipped stdout](plumed_tor.dat.plumed.stdout.txt.zip) - [stderr](plumed_tor.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [stderr](plumed_tor.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue"># Define Torsional angles</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n_s.html">TORSIONS</a> ...
ATOMS1=74,79,70,73
ATOMS2=107,112,103,106
ATOMS3=206,211,202,205
ATOMS4=239,244,235,238
...
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s141_=9314_,9319_,9310_,9313.html">ATOMS141=9314,9319,9310,9313</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s142_=9347_,9352_,9343_,9346.html">ATOMS142=9347,9352,9343,9346</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s143_=9446_,9451_,9442_,9445.html">ATOMS143=9446,9451,9442,9445</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s144_=9479_,9484_,9475_,9478.html">ATOMS144=9479,9484,9475,9478</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_l_a_b_e_l_=_g_l_o_b_a_l.html">LABEL=Global</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_._._..html">...</a> TORSI<a href="https://plumed.github.io/doc-master/user-doc/html/_._._..html">...</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_t_o_r_s_i_o_n_s.html">TORSIONS</a> ...
ATOMS1=76,79,74,75
ATOMS2=109,112,107,108
ATOMS3=208,211,206,207
ATOMS4=241,244,239,240
...
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s141_=9316_,9319_,9314_,9315.html">ATOMS141=9316,9319,9314,9315</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s142_=9349_,9352_,9347_,9348.html">ATOMS142=9349,9352,9347,9348</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s143_=9448_,9451_,9446_,9447.html">ATOMS143=9448,9451,9446,9447</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_a_t_o_m_s144_=9481_,9484_,9479_,9480.html">ATOMS144=9481,9484,9479,9480</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_l_a_b_e_l_=_l_o_c_a_l.html">LABEL=Local</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_._._..html">...</a> TORSI<a href="https://plumed.github.io/doc-master/user-doc/html/_._._..html">...</a>

<span style="color:blue"># Plot 2D distribution</span>
kde_Stor: <a href="https://plumed.github.io/doc-master/user-doc/html/_k_d_e.html">KDE</a> ARG1=Global ARG2=Local  GRID_MIN=-3.142,-3.142 GRID_MAX=3.142,3.142 GRID_BIN=73,73 BANDWIDTH=0.250,0.250 KERNEL=GAUSSIAN

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=kde_Stor FILE=plumed_md_tor.dat
</pre>{% endraw %}
