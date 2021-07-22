**Project ID:** [plumID:21.027]({{ '/' | absolute_url }}eggs/21/027/)  
**Source:** A763-Y764insFQEA/plumed.dat  
**Originally used with PLUMED version:** 2.4  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_s_t_a_r_t.html">RESTART</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_o_l_i_n_f_o.html">MOLINFO</a> STRUCTURE=npt_FQEA.pdb
<a href="https://plumed.github.io/doc-master/user-doc/html/_w_h_o_l_e_m_o_l_e_c_u_l_e_s.html">WHOLEMOLECULES</a> ENTITY0=1-4779
<span style="color:blue"># Distances describing the two saltbridges K745(NZ):E762(CD) and K745(ΝΖ):D855(CG)</span>
<span style="color:blue"># that reflect the conformation of the aC helix</span>
<span style="color:blue"># (CVs described in Ludo's paper doi:10.1073/pnas.1221953110)</span>

K745_E762: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=745,1078
K745_D855: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=745,2583

<span style="color:blue"># Distance between the two distance</span>
<span style="color:blue"># When both saltbridges are formed, the distance between the two distances (CV)</span>
<span style="color:blue"># is close to 0. This CV is able to characterise the displacement of the fuctionally important</span>
<span style="color:blue"># E762 located in the aC helix of the N-lobe in its transition from the so-called "aC-in" to "aC-out" conformation</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ...
    LABEL=d
    ARG=K745_E762,K745_D855
    VAR=a,b
    FUNC=a-b
    PERIODIC=NO
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a>

<span style="color:blue"># Distance from active cmap</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="cmap_active_fqea.dat.html">cmap_active_fqea.dat</a>

<span style="color:blue"># Distance form inactive cmap</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_i_n_c_l_u_d_e.html">INCLUDE</a> FILE=<a href="cmap_inactive_fqea.dat.html">cmap_inactive_fqea.dat</a>

<span style="color:blue"># Confine the explored space</span>
lwall: <a href="https://plumed.github.io/doc-master/user-doc/html/_l_o_w_e_r__w_a_l_l_s.html">LOWER_WALLS</a> ARG=d AT=-1.5 KAPPA=4000.0
uwall: <a href="https://plumed.github.io/doc-master/user-doc/html/_u_p_p_e_r__w_a_l_l_s.html">UPPER_WALLS</a> ARG=cmap_active,cmap_inactive,d AT=90,90,2.5 KAPPA=3500.0,3500.0,4000.0

<span style="color:blue"># Activate metaD in energy (Well Tempered Ensemble) </span>
<span style="color:blue"># Gaussians from an initial metaD sim where the energy was biased</span>
<span style="color:blue"># will be loaded to perform the second metaD in the WTE</span>
ene: <a href="https://plumed.github.io/doc-master/user-doc/html/_e_n_e_r_g_y.html">ENERGY</a>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
    LABEL=wte
    ARG=ene PACE=1000000 HEIGHT=2 SIGMA=100 <span style="color:blue"># Deposit a Gaussian to the potential energy every 2 ns</span>
    FILE=HILLS_PTWE
    BIASFACTOR=15 TEMP=@<a href="https://plumed.github.io/doc-master/user-doc/html/special-replica-syntax.html">replicas</a>:300,305,310,318,326,335,344,354,363,375,382
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a>

<span style="color:blue"># Activate metaD on the rest of the CVs</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
    LABEL=meta
    ARG=cmap_active,cmap_inactive,d HEIGHT=3.0 SIGMA=0.75,0.75,0.15 PACE=500 
    GRID_MIN=0,0,-2 GRID_MAX=95,95,3 GRID_SPACING=0.35,0.35,0.075 
    BIASFACTOR=10 TEMP=@<a href="https://plumed.github.io/doc-master/user-doc/html/special-replica-syntax.html">replicas</a>:300,305,310,318,326,335,344,354,363,375,382
... <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=* STRIDE=500 FILE=COLVAR FMT=%8.4f

</pre>{% endraw %}
