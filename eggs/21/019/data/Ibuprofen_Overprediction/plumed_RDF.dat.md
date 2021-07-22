**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
**Source:** Ibuprofen_Overprediction/plumed_RDF.dat  
**Originally used with PLUMED version:** 2.5-mod  
**Stable:** [raw zipped stdout](plumed_RDF.dat.plumed.stdout.txt.zip) - [stderr](plumed_RDF.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed_RDF.dat.plumed_master.stdout.txt.zip) - [stderr](plumed_RDF.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue"># Define Centers of atoms (Mass-Charge file required)</span>
RDF_c1: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=1,2,4,6,7,8,10,11,13,16,18,20,22,26,30
RDF_c2: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=34,35,37,39,40,41,43,44,46,49,51,53,55,59,63
RDF_c3: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=67,68,70,72,73,74,76,77,79,82,84,86,88,92,96
RDF_c4: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=100,101,103,105,106,107,109,110,112,115,117,119,121,125,129
<a href="https://plumed.github.io/doc-master/user-doc/html/_._._..html">...</a>
RDF_c284: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=9340,9341,9343,9345,9346,9347,9349,9350,9352,9355,9357,9359,9361,9365,9369
RDF_c285: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=9373,9374,9376,9378,9379,9380,9382,9383,9385,9388,9390,9392,9394,9398,9402
RDF_c286: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=9406,9407,9409,9411,9412,9413,9415,9416,9418,9421,9423,9425,9427,9431,9435
RDF_c287: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=9439,9440,9442,9444,9445,9446,9448,9449,9451,9454,9456,9458,9460,9464,9468
RDF_c288: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m.html">COM</a> ATOMS=9472,9473,9475,9477,9478,9479,9481,9482,9484,9487,9489,9491,9493,9497,9501

<span style="color:blue"># Calculate the distances and plot distribution</span>
RDF_g: <a href="https://plumed.github.io/doc-master/user-doc/html/_g_r_o_u_p.html">GROUP</a> ATOMS=RDF_c1,RDF_c2,RDF_c3,RDF_c4,...,RDF_c285,RDF_c286,RDF_c287,RDF_c288
RDF_d: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e_s.html">DISTANCES</a> GROUP=RDF_g MORE_THAN={RATIONAL R_0=0.01 D_0=2.09 D_MAX=2.09} HISTOGRAM={TRIANGULAR NBINS=208 BANDWIDTH=0.01 UPPER=2.09 LOWER=0.01}
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=RDF_d.* FILE=plumed_md_RDF.dat

</pre>{% endraw %}
