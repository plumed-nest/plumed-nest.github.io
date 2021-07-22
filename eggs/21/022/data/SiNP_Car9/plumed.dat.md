**Project ID:** [plumID:21.022]({{ '/' | absolute_url }}eggs/21/022/)  
**Source:** SiNP_Car9/plumed.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">## RESTART</span>

<a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_l_i_n_f_o.html">MOLINFO</a> MOLTYPE=protein STRUCTURE=car9_ACE_NME.pdb

<a href="https://plumed.github.io/doc-master/user-doc/html/_e_n_e_r_g_y.html">ENERGY</a> LABEL=energy

ncap: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11713-11718
ccap: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11914-11919

bb: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11717,11718,11719,11729,11730,11731,11740,11741,11742,11750,11751,11752,11774,11775,11776,11781,11782,11783,11801,11802,11803,11823,11824,11825,11845,11846,11847,11859,11860,11861,11866,11867,11868,11888,11889,11890,11912,11913,11914

asp: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11720-11728
ser: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11732-11739
ala: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11743-11749
arg: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11753-11773
gly: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11777-11780
phe: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11784-11800
lys: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11804-11822
lys2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11826-11844
pro: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11848-11858
gly2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11862-11865
lys3: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11869-11887
arg2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=11891-11911

top_oh: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=78,177,385,439,459,497,570,601,634,637,640,643,644,648,653,660,662,684,709,734,795,898,1036,1041,1110,1184,1222,1295,1328,1365,1368,1371,1373,1376,1377,1382,1389,1412,1438,1521,1620,1759,1829,1883,1903,1941,2014,2042,2046,2079,2082,2085,2087,2089,2093,2098,2105,2106,2107,2128,2153,2156,2183,2244,2347,2490,2560,2614,2634,2672,2745,2778,2815,2818,2821,2823,2826,2827,2832,2838,2861,2886,2892,2908,3006,3105,3313,3367,3387,3425,3498,3529,3562,3565,3568,3571,3572,3576,3581,3588,3590,3612,3637,3662,3723,3826,3964,3969,4038,4112,4150,4223,4256,4293,4296,4299,4301,4304,4305,4310,4317,4340,4366,4449,4548,4687,4757,4811,4831,4869,4942,4970,4974,5007,5010,5013,5015,5017,5021,5026,5033,5034,5035,5056,5081,5084,5111,5172,5275,5418,5488,5542,5562,5600,5673,5706,5743,5746,5749,5751,5754,5755,5760,5766,5789,5814,5820,5836,5934,6033,6241,6295,6315,6353,6426,6457,6490,6493,6496,6499,6500,6504,6509,6516,6518,6540,6565,6590,6651,6754,6892,6897,6966,7040,7078,7151,7184,7221,7224,7227,7229,7232,7233,7238,7245,7268,7294,7377,7476,7615,7685,7739,7759,7797,7870,7898,7902,7935,7938,7941,7943,7945,7949,7954,7961,7962,7963,7984,8009,8012,8039,8100,8203,8346,8416,8470,8490,8528,8601,8634,8671,8674,8677,8679,8682,8683,8688,8694,8717,8742,8748,8764,8862,8961,9169,9223,9243,9281,9354,9385,9418,9421,9424,9427,9428,9432,9437,9444,9446,9468,9493,9518,9579,9682,9820,9825,9894,9968,10006,10079,10112,10149,10152,10155,10157,10160,10161,10166,10173,10196,10222,10305,10404,10543,10613,10667,10687,10725,10798,10826,10830,10863,10866,10869,10871,10873,10877,10882,10889,10890,10891,10912,10937,10940,10967,11028,11131,11274,11344,11398,11418,11456,11529,11562,11599,11602,11605,11607,11610,11611,11616,11622,11645,11670,11676,11692

dcaps: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=ncap,ccap 
dncap: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,ncap COMPONENTS NOPBC
dccap: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,ccap COMPONENTS NOPBC

dbb: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,bb COMPONENTS NOPBC
dasp: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,asp COMPONENTS NOPBC
dser: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,ser COMPONENTS NOPBC
dala: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,ala COMPONENTS NOPBC
darg: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,arg COMPONENTS NOPBC
dgly: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,gly COMPONENTS NOPBC
dphe: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,phe COMPONENTS NOPBC
dlys: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,lys COMPONENTS NOPBC
dlys2: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,lys2 COMPONENTS NOPBC
dpro: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,pro COMPONENTS NOPBC
dgly2: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,gly2 COMPONENTS NOPBC
dlys3: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,lys3 COMPONENTS NOPBC
darg2: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=top_oh,arg2 COMPONENTS NOPBC


<a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html">LOWER_WALLS</a> ARG=dcaps AT=0.8 KAPPA=100000 LABEL=dcaps_min
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dcaps AT=1.8 KAPPA=100000 LABEL=dcaps_max
<a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html">LOWER_WALLS</a> ARG=dncap.z AT=0.5 KAPPA=1000000 LABEL=dncap_min
<a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html">LOWER_WALLS</a> ARG=dccap.z AT=0.5 KAPPA=1000000 LABEL=dccap_min

<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dbb.z AT=6.5 KAPPA=1000000 LABEL=uwall_dbb
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dasp.z AT=6.5 KAPPA=1000000 LABEL=uwall_dasp
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dser.z AT=6.5 KAPPA=1000000 LABEL=uwall_dser
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dala.z AT=6.5 KAPPA=1000000 LABEL=uwall_dala
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=darg.z AT=6.5 KAPPA=1000000 LABEL=uwall_darg
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dgly.z AT=6.5 KAPPA=1000000 LABEL=uwall_dgly
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dphe.z AT=6.5 KAPPA=1000000 LABEL=uwall_dphe
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dlys.z AT=6.5 KAPPA=1000000 LABEL=uwall_dlys
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dlys2.z AT=6.5 KAPPA=1000000 LABEL=uwall_dlys2
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dpro.z AT=6.5 KAPPA=1000000 LABEL=uwall_dpro
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dgly2.z AT=6.5 KAPPA=1000000 LABEL=uwall_dgly2
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=dlys3.z AT=6.5 KAPPA=1000000 LABEL=uwall_dlys3
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=darg2.z AT=6.5 KAPPA=1000000 LABEL=uwall_darg2

<a href="https://plumed.github.io/doc-master/user-doc/html/_g_y_r_a_t_i_o_n.html">GYRATION</a> TYPE=RADIUS ATOMS=11713-11919 LABEL=rg

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_b_m_e_t_a_d.html">PBMETAD</a> ...
WALKERS_MPI
ARG=dbb.z,dasp.z,dser.z,dala.z,darg.z,dgly.z,dphe.z,dlys.z,dlys2.z,dpro.z,dgly2.z,dlys3.z,darg2.z,rg
SIGMA=0.02,0.02,0.02,0.02,0.02,0.02,0.02,0.02,0.02,0.02,0.02,0.02,0.02,0.02
HEIGHT=1.2 <span style="color:blue">#kJ/mol</span>
PACE=1000
BIASFACTOR=20
TEMP=298.0
LABEL=<a href="https://plumed.github.io/doc-master/user-doc/html/_p_b_m_e_t_a_d.html">PBMETAD</a>
GRID_MIN=-1.0,-1.0,-1.0,-1.0,-1.0,-1.0,-1.0,-1.0,-1.0,-1.0,-1.0,-1.0,-1.0,0.0
GRID_MAX=9.0,9.0,9.0,9.0,9.0,9.0,9.0,9.0,9.0,9.0,9.0,9.0,9.0,8
FILE=HILLS.dbb,HILLS.dasp,HILLS.dser,HILLS.dala,HILLS.darg,HILLS.dgly,HILLS.dphe,HILLS.dlys,HILLS.dlys2,HILLS.dpro,HILLS.dgly2,HILLS.dlys3,HILLS.darg2,HILLS.rg
... <a href="https://plumed.github.io/doc-master/user-doc/html/_p_b_m_e_t_a_d.html">PBMETAD</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=dcaps,dbb.z,dncap.z,dccap.z,dasp.z,dser.z,dala.z,darg.z,dgly.z,dphe.z,dlys.z,dlys2.z,dpro.z,dgly2.z,dlys3.z,darg2.z,rg,energy,PBMETAD.bias STRIDE=500 FILE=COLVAR




</pre>{% endraw %}
