**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
**Source:** meta_reweigthing/6_D_adaptive/plumed.dat  
**Originally used with PLUMED version:** 2.5-mod  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue"># plumed input file</span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> NATURAL
d1: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1,2 COMPONENTS
d2: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1,3 COMPONENTS

ff: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_a_t_h_e_v_a_l.html">MATHEVAL</a> ARG=d1.x,d1.y,d1.z,d2.x,d2.y,d2.z VAR=x0,x1,x2,x3,x4,x5 PERIODIC=NO FUNC=4.0*exp(-4.0*(x0-1.0)^2-4.0*(x1-1.0)^2-4.0*(x2-1.0)^2-4.0*(x3-1.0)^2-4.0*(x4-1.0)^2-4.0*(x5-1.0)^2)+4.0*exp(-4.0*(x0-1.0)^2-4.0*(x1-1.0)^2-4.0*(x2-1.0)^2-4.0*(x3+1.0)^2-4.0*(x4+1.0)^2-4.0*(x5+1.0)^2)+4.0*exp(-4.0*(x0+1.0)^2-4.0*(x1+1.0)^2-4.0*(x2+1.0)^2-4.0*(x3+1.0)^2-4.0*(x4+1.0)^2-4.0*(x5+1.0)^2)+4.0/(1.0/((5.0*x0+5.0)^2+(5.0*x1+5.0)^2+(5.0*x2+5.0)^2+(5.0*x3+5.0)^2+(5.0*x4+5.0)^2+(5.0*x5+5.0)^2+1)+1.0/((5.0*x0-5.0)^2+(5.0*x1-5.0)^2+(5.0*x2-5.0)^2+(5.0*x3+5.0)^2+(5.0*x4+5.0)^2+(5.0*x5+5.0)^2+1)+1.0/((5.0*x0-5.0)^2+(5.0*x1-5.0)^2+(5.0*x2-5.0)^2+(5.0*x3-5.0)^2+(5.0*x4-5.0)^2+(5.0*x5-5.0)^2+1)+1.0/((-2.04124145231931*x0-0.591751709536137*x1-0.591751709536137*x2-0.591751709536137*x3-0.591751709536137*x4+4.40824829046386*x5)^2.0+(-2.04124145231931*x0-0.591751709536137*x1-0.591751709536137*x2-0.591751709536137*x3+4.40824829046386*x4-0.591751709536137*x5)^2.0+(-2.04124145231931*x0-0.591751709536137*x1-0.591751709536137*x2+4.40824829046386*x3-0.591751709536137*x4-0.591751709536137*x5)^2.0+(-2.04124145231931*x0-0.591751709536137*x1+4.40824829046386*x2-0.591751709536137*x3-0.591751709536137*x4-0.591751709536137*x5)^2.0+(-2.04124145231931*x0+4.40824829046386*x1-0.591751709536137*x2-0.591751709536137*x3-0.591751709536137*x4-0.591751709536137*x5)^2.0+(0.408248290463863*x0+0.408248290463863*x1+0.408248290463863*x2+0.408248290463863*x3+0.408248290463863*x4+0.408248290463863*x5)^8.0)+1.0/((5.0*x3+5.0)^2.0+(5.0*x4+5.0)^2.0+(5.0*x5+5.0)^2.0+(-2.88675134594813*x0-1.05662432702594*x1+3.94337567297406*x2)^2.0+(-2.88675134594813*x0+3.94337567297406*x1-1.05662432702594*x2)^2.0+(0.577350269189626*x0+0.577350269189626*x1+0.577350269189626*x2)^8.0)+1.0/((5.0*x1-5.0)^2.0+(5.0*x2-5.0)^2.0+(0.577350269189626*x3+0.577350269189626*x4+0.577350269189626*x5)^8.0+(-2.88675134594813*x0-1.66666666666667*x3-1.66666666666667*x4+3.33333333333333*x5+2.88675134594813)^2.0+(-2.88675134594813*x0-1.66666666666667*x3+3.33333333333333*x4-1.66666666666667*x5+2.88675134594813)^2.0+(-2.88675134594813*x0+3.33333333333333*x3-1.66666666666667*x4-1.66666666666667*x5+2.88675134594813)^2.0))


bb: <a href="https://plumed.github.io/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html">BIASVALUE</a> ARG=ff

mt: <a href="https://plumed.github.io/doc-master/user-doc/html/_m_e_t_a_d.html">METAD</a> ...
ARG=d1.x,d1.y,d1.z,d2.x,d2.y,d2.z PACE=500
ADAPTIVE=DIFF
SIGMA=400
SIGMA_MAX=0.05,0.05,0.05,0.05,0.05,0.05
HEIGHT=10.0 BIASFACTOR=3 TEMP=1
...


<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=mt.bias FILE=rr.bias_500 STRIDE=500
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_a_t_o_m_s.html">DUMPATOMS</a> STRIDE=500 FILE=traj.xyz ATOMS=1,2,3


</pre>{% endraw %}