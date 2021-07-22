**Project ID:** [plumID:21.023]({{ '/' | absolute_url }}eggs/21/023/)  
**Source:** Data-mb/mb-wtm-bf7/./MuellerBrown-Potential.dat  
{% raw %}<pre>
<span style="color:blue"># <a href="https://plumed.github.io/doc-master/user-doc/html/_vim_syntax.html">vim:ft=plumed</a></span>
<a href="https://plumed.github.io/doc-master/user-doc/html/_u_n_i_t_s.html">UNITS</a> NATURAL

<span style="color:blue"># Müller-Brown potential, sum of four terms</span>
<span style="color:blue">#-200*exp( -(x-1)^2 -10*y^2 )</span>
<span style="color:blue">#-100*exp( -x^2 -10*(y-0.5)^2 )</span>
<span style="color:blue">#-170*exp( -6.5*(x+0.5)^2 + 11*(x+0.5)*(y-1.5) -6.5*(y-1.5)^2 )</span>
<span style="color:blue"># +15*exp(  0.7*(x+1)^2 +0.6*(x+1)*(y-1) +0.7*(y-1)^2 )</span>
<span style="color:blue"># Shifted by 146.699489200588 to have a zero value </span>
<span style="color:blue"># at the global minimum ( -0.558 , 1.442 )</span>
<span style="color:blue"># Minima: ( -0.558 , 1.442 ) [ Value: 0.0 ]</span>
<span style="color:blue">#         (  0.623 , 0.028 ) [ Value: 38.532839 ]</span>
<span style="color:blue">#         ( -0.050 , 0.467 ) [ Value: 65.931740 ] </span>
<span style="color:blue"># Saddle Points : ( -0.822 ,  0.624 ) [ Value: 106.034644 ]</span>
<span style="color:blue">#                 ( -0.212 ,  0.293 ) [ Value: 88.435607 ]</span>
<span style="color:blue"># Can be scaled via the scaling_factor </span>
<span style="color:blue"># (above values for minima and saddle points are then scaled)</span>

scaling_factor: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_s_t_a_n_t.html">CONSTANT</a> VALUE=0.2

p: <a href="https://plumed.github.io/doc-master/user-doc/html/_d_i_s_t_a_n_c_e.html">DISTANCE</a> ATOMS=1,2 COMPONENTS
<a href="https://plumed.github.io/doc-master/user-doc/html/_c_u_s_t_o_m.html">CUSTOM</a> ...
 LABEL=pot
 ARG=p.x,p.y,scaling_factor 
 VAR=x,y,sf
 FUNC=sf*(-200*exp(-(x-1)^2-10*y^2)-100*exp(-x^2-10*(y-0.5)^2)-170*exp(-6.5*(x+0.5)^2+11*(x+0.5)*(y-1.5)-6.5*(y-1.5)^2)+15*exp(0.7*(x+1)^2+0.6*(x+1)*(y-1)+0.7*(y-1)^2)+146.699489200588)
 PERIODIC=NO 
... <a href="https://plumed.github.io/doc-master/user-doc/html/_c_u_s_t_o_m.html">CUSTOM</a>
bv: <a href="https://plumed.github.io/doc-master/user-doc/html/_b_i_a_s_v_a_l_u_e.html">BIASVALUE</a> ARG=pot
</pre>{% endraw %}
