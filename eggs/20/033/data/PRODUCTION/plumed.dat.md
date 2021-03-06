**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
**Source:** PRODUCTION/plumed.dat  
**Originally used with PLUMED version:** 2.6  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue">#RESTART</span>

<a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_l_i_n_f_o.html">MOLINFO</a> STRUCTURE=structure.pdb
<span style="color:blue"># define all heavy atoms using GROMACS index file</span>

protein-h: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> NDX_FILE=index.ndx NDX_GROUP=Protein-H
protein: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> NDX_FILE=index.ndx NDX_GROUP=Protein
Protein-noASPGLU-noH: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> NDX_FILE=index.ndx NDX_GROUP=Protein-H_&_!GLU_ASP_&_OE1_OE2_OD1_OD2
system: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> NDX_FILE=index.ndx NDX_GROUP=System
<span style="color:blue"># make protein whole: add reference position of first heavy atom (in nm)</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=1-19086 ENTITY1=19087-38172 ENTITY2=38173-57258 ADDREFERENCE REF0=16.995,21.964,24.520 REF1=26.253,18.440,24.5030 REF2=24.616,28.069,24.203

<a href="https://plumed.github.io/doc-master/user-doc/html/_r_m_s_d.html">RMSD</a> REFERENCE=6vxx_1_1_1_aligned_struct_RBD_renumbered.pdb TYPE=OPTIMAL LABEL=rmsd_closed_charmm_6vxx
<a href="https://plumed.github.io/doc-master/user-doc/html/_r_m_s_d.html">RMSD</a> REFERENCE=rmsd_structure_no487496.pdb TYPE=OPTIMAL LABEL=rmsd_open

gly234NTFdown:  <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e_s.html">DISTANCES</a> GROUPA=3316,3318,3320,3323,3324,3325,3327,3328,17553,17555,17556,17558,17561,17563,17565,17567,17569,17571,17573,17574,17575,17579,17580,17582,17583,17585,17588,17590,17592,17594,17596,17598,17600,17601,17602,17606,17607,17609,17610,17612,17615,17616,17618,17620,17622,17624,17626,17627,17629,17631,17633,17635,17637,17640,17642,17643,17645,17647,17649,17651,17653,17655,17657,17659,17662,17664,17665,17667,17669 GROUPB=43296,43298,43300,43303,43304,43306,43308,43309,43311,43313,43315,43316,43317,43319,43321,43325,43326,44813,44815,44817,44820,44821,44822,44825,44826,44827,44829,44831,44834,44835,44837,44839,44840,44842,44844,44846,44847,44848,44850,44852,44855,44857,44861,44865,44866,44951,44953,44955,44958,44961,44964,44966,44967,44970,44973,44974,45041,45043,45045,45048,45051,45054,45057,45061,45062,45097,45099,45101,45104,45107,45108,45109,45110,45111,45112,45114,45116,45119,45122,45125,45127,45128,45131,45134,45135,45136,45138,45140,45143,45144,45145,45146,45147,45148,45150,45152,45154,45158,45161,45165,45166,45178,45180,45182,45184,45188,45190,45191,45192,45194,45196,45199,45202,45203,45204,45205,45206,45247,45249,45251,45254,45257,45258,45259,45262,45263 LESS_THAN={RATIONAL R_0=0.32 NN=6 MM=12}


gly165NTF_up:  <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e_s.html">DISTANCES</a> GROUPA=2196,2198,2200,2203,2204,2205,2207,2208,17435,17437,17438,17440,17443,17445,17447,17449,17451,17453,17455,17456,17457,17461,17462,17464,17465,17467,17470,17472,17474,17476,17478,17480,17482,17483,17484,17488,17489,17491,17492,17494,17497,17498,17500,17502,17504,17506,17508,17509,17511,17513,17515,17517,17519,17522,17524,17525,17527,17529,17531,17533,17535,17537,17539,17541,17544,17546,17547,17549,17551 GROUPB=43296,43298,43300,43303,43304,43306,43308,43309,43311,43313,43315,43316,43317,43319,43321,43325,43326,44813,44815,44817,44820,44821,44822,44825,44826,44827,44829,44831,44834,44835,44837,44839,44840,44842,44844,44846,44847,44848,44850,44852,44855,44857,44861,44865,44866,44951,44953,44955,44958,44961,44964,44966,44967,44970,44973,44974,45041,45043,45045,45048,45051,45054,45057,45061,45062,45097,45099,45101,45104,45107,45108,45109,45110,45111,45112,45114,45116,45119,45122,45125,45127,45128,45131,45134,45135,45136,45138,45140,45143,45144,45145,45146,45147,45148,45150,45152,45154,45158,45161,45165,45166,45178,45180,45182,45184,45188,45190,45191,45192,45194,45196,45199,45202,45203,45204,45205,45206,45247,45249,45251,45254,45257,45258,45259,45262,45263 LESS_THAN={RATIONAL R_0=0.32 NN=6 MM=12}

<span style="color:blue"># create EMMI score</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_e_m_m_i.html">EMMI</a> ...
LABEL=gmm NOPBC TEMP=310.0 NL_STRIDE=100 NL_CUTOFF=0.01
ATOMS=Protein-noASPGLU-noH GMM_FILE=SARS_COV2.dat
SIGMA_MIN=0.05 RESOLUTION=0.1 NOISETYPE=MARGINAL
<span style="color:blue">#WRITE_OV=OV_FILE.dat </span>
<span style="color:blue">#WRITE_OV_STRIDE=500</span>
...

<span style="color:blue"># translate into bias</span>
emr: <a href="https://plumed.github.io/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html">BIASVALUE</a> ARG=gmm.scoreb STRIDE=2

<span style="color:blue"># print useful info to file</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=* FILE=COLVAR STRIDE=5000

</pre>{% endraw %}
