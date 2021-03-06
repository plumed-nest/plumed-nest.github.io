**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
**Source:** plumed_reweight.dat  
**Originally used with PLUMED version:** not specified  
**Stable:** [raw zipped stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [stderr](plumed_reweight.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [stderr](plumed_reweight.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue"># The consequence of including this command is that the bias values that are calculated</span>
<span style="color:blue"># by the METAD action are values for the final simulation bias.</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_s_t_a_r_t.html">RESTART</a>
<span style="color:blue"># These two commands recompute the CV that was biased in the metadynamics calculation.</span>
d1: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_e_n_s_i_t_y.html">DENSITY</a> SPECIES=2-2400:12,10-2400:12 LOWMEM
cont: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e__f_r_o_m__c_o_n_t_o_u_r.html">DISTANCE_FROM_CONTOUR</a> ...
   DATA=d1  ATOM=2413  BANDWIDTH=3.0,3.0,3.0  DIR=z  CONTOUR=0.42
...
 <span style="color:blue"># This command is used to calculate the final metadynamics bias.  This quantity is</span>
 <span style="color:blue"># required because it used when reweighting each of the trajectory frames.</span>
 mm: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
   ARG=cont.qdist SIGMA=0.5 HEIGHT=1.3 BIASFACTOR=25 TEMP=325
   PACE=2000000000  <span style="color:blue"># This is large so Gaussians are not added and the bias is constant.</span>
   GRID_MIN=-15.0 GRID_MAX=100.0 GRID_BIN=115000
   ADAPTIVE=GEOM SIGMA_MIN=0.05  SIGMA_MAX=6.00
 ...
 uwall: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=cont.qdist AT=50.0 KAPPA=1.0 EXP=2
 <span style="color:blue"># The two lines below instruct PLUMED to calculate the distance between the adsorbate and</span>
 <span style="color:blue"># the isosurface.  Notice, however, that, because we are now doing the analysis all of</span>
 <span style="color:blue"># the atoms in the membrane are used when we calculate the density.</span>
d2: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_e_n_s_i_t_y.html">DENSITY</a> SPECIES=1-2400
cont2: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e__f_r_o_m__c_o_n_t_o_u_r.html">DISTANCE_FROM_CONTOUR</a> ...
   DATA=d2  ATOM=2413  BANDWIDTH=0.6,0.6,0.6  DIR=z  CONTOUR=7.29
...
 <span style="color:blue"># When reweighting we must take both the MEAD and UPPER_WALLS into account</span>
bias: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> ARG=*.bias PERIODIC=NO
<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=cont2.*,bias FILE=COLVAR-reweight STRIDE=1
</pre>{% endraw %}
