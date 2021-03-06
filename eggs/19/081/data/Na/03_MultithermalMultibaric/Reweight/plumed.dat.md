**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
**Source:** Na/03_MultithermalMultibaric/Reweight/plumed.dat  
**Originally used with PLUMED version:** 2.6-dev  
**Stable:** [raw zipped stdout](plumed.dat.plumed.stdout.txt.zip) - [stderr](plumed.dat.plumed.stderr)  
**Master:** [raw zipped stdout](plumed.dat.plumed_master.stdout.txt.zip) - [stderr](plumed.dat.plumed_master.stderr)  

{% raw %}<pre>
<span style="color:blue"># <a href="https://plumed.github.io/doc-master/user-doc/html/_vim_syntax.html">vim:ft=plumed</a></span>

energy: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_a_d.html">READ</a> FILE=COLVARtrim VALUES=energy  IGNORE_TIME
b1: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_a_d.html">READ</a> FILE=COLVARtrim VALUES=b1.bias  IGNORE_TIME
uwall: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_a_d.html">READ</a> FILE=COLVARtrim VALUES=uwall.bias IGNORE_TIME
refcv: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_a_d.html">READ</a> FILE=COLVARtrim VALUES=refcv.morethan  IGNORE_TIME
voltmp: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_a_d.html">READ</a> FILE=COLVARtrim VALUES=vol  IGNORE_TIME

vol: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> ARG=voltmp PARAMETERS=10.0 PERIODIC=NO
renergy: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_m_b_i_n_e.html">COMBINE</a> ARG=energy PARAMETERS=-25000 PERIODIC=NO
weights: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__b_i_a_s.html">REWEIGHT_BIAS</a> TEMP=400. ARG=b1.bias,uwall.bias

weights350-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=350.0 REWEIGHT_PRESSURE=0.0 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights350-0
  NORMALIZATION=true
  LABEL=hh350-0
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh350-0 FILE=histo350-0 STRIDE=10000 FMT=%16.10f
ff350-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh350-0 TEMP=350.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff350-0 FILE=fes350-0 STRIDE=10000 FMT=%16.10f

weights350-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=350.0 REWEIGHT_PRESSURE=60.22140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights350-1000
  NORMALIZATION=true
  LABEL=hh350-1000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh350-1000 FILE=histo350-1000 STRIDE=10000 FMT=%16.10f
ff350-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh350-1000 TEMP=350.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff350-1000 FILE=fes350-1000 STRIDE=10000 FMT=%16.10f

weights350-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=350.0 REWEIGHT_PRESSURE=120.44281714 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights350-2000
  NORMALIZATION=true
  LABEL=hh350-2000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh350-2000 FILE=histo350-2000 STRIDE=10000 FMT=%16.10f
ff350-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh350-2000 TEMP=350.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff350-2000 FILE=fes350-2000 STRIDE=10000 FMT=%16.10f

weights350-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=350.0 REWEIGHT_PRESSURE=180.66422571 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights350-3000
  NORMALIZATION=true
  LABEL=hh350-3000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh350-3000 FILE=histo350-3000 STRIDE=10000 FMT=%16.10f
ff350-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh350-3000 TEMP=350.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff350-3000 FILE=fes350-3000 STRIDE=10000 FMT=%16.10f

weights350-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=350.0 REWEIGHT_PRESSURE=240.88563428 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights350-4000
  NORMALIZATION=true
  LABEL=hh350-4000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh350-4000 FILE=histo350-4000 STRIDE=10000 FMT=%16.10f
ff350-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh350-4000 TEMP=350.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff350-4000 FILE=fes350-4000 STRIDE=10000 FMT=%16.10f

weights350-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=350.0 REWEIGHT_PRESSURE=301.10704285 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights350-5000
  NORMALIZATION=true
  LABEL=hh350-5000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh350-5000 FILE=histo350-5000 STRIDE=10000 FMT=%16.10f
ff350-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh350-5000 TEMP=350.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff350-5000 FILE=fes350-5000 STRIDE=10000 FMT=%16.10f

weights350-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=350.0 REWEIGHT_PRESSURE=361.32845142 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights350-6000
  NORMALIZATION=true
  LABEL=hh350-6000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh350-6000 FILE=histo350-6000 STRIDE=10000 FMT=%16.10f
ff350-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh350-6000 TEMP=350.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff350-6000 FILE=fes350-6000 STRIDE=10000 FMT=%16.10f

weights350-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=350.0 REWEIGHT_PRESSURE=421.54985999 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights350-7000
  NORMALIZATION=true
  LABEL=hh350-7000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh350-7000 FILE=histo350-7000 STRIDE=10000 FMT=%16.10f
ff350-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh350-7000 TEMP=350.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff350-7000 FILE=fes350-7000 STRIDE=10000 FMT=%16.10f

weights350-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=350.0 REWEIGHT_PRESSURE=481.77126856 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights350-8000
  NORMALIZATION=true
  LABEL=hh350-8000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh350-8000 FILE=histo350-8000 STRIDE=10000 FMT=%16.10f
ff350-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh350-8000 TEMP=350.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff350-8000 FILE=fes350-8000 STRIDE=10000 FMT=%16.10f

weights350-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=350.0 REWEIGHT_PRESSURE=541.9926771300001 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights350-9000
  NORMALIZATION=true
  LABEL=hh350-9000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh350-9000 FILE=histo350-9000 STRIDE=10000 FMT=%16.10f
ff350-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh350-9000 TEMP=350.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff350-9000 FILE=fes350-9000 STRIDE=10000 FMT=%16.10f

weights350-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=350.0 REWEIGHT_PRESSURE=602.2140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights350-10000
  NORMALIZATION=true
  LABEL=hh350-10000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh350-10000 FILE=histo350-10000 STRIDE=10000 FMT=%16.10f
ff350-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh350-10000 TEMP=350.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff350-10000 FILE=fes350-10000 STRIDE=10000 FMT=%16.10f

weights360-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=360.0 REWEIGHT_PRESSURE=0.0 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights360-0
  NORMALIZATION=true
  LABEL=hh360-0
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh360-0 FILE=histo360-0 STRIDE=10000 FMT=%16.10f
ff360-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh360-0 TEMP=360.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff360-0 FILE=fes360-0 STRIDE=10000 FMT=%16.10f

weights360-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=360.0 REWEIGHT_PRESSURE=60.22140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights360-1000
  NORMALIZATION=true
  LABEL=hh360-1000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh360-1000 FILE=histo360-1000 STRIDE=10000 FMT=%16.10f
ff360-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh360-1000 TEMP=360.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff360-1000 FILE=fes360-1000 STRIDE=10000 FMT=%16.10f

weights360-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=360.0 REWEIGHT_PRESSURE=120.44281714 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights360-2000
  NORMALIZATION=true
  LABEL=hh360-2000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh360-2000 FILE=histo360-2000 STRIDE=10000 FMT=%16.10f
ff360-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh360-2000 TEMP=360.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff360-2000 FILE=fes360-2000 STRIDE=10000 FMT=%16.10f

weights360-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=360.0 REWEIGHT_PRESSURE=180.66422571 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights360-3000
  NORMALIZATION=true
  LABEL=hh360-3000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh360-3000 FILE=histo360-3000 STRIDE=10000 FMT=%16.10f
ff360-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh360-3000 TEMP=360.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff360-3000 FILE=fes360-3000 STRIDE=10000 FMT=%16.10f

weights360-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=360.0 REWEIGHT_PRESSURE=240.88563428 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights360-4000
  NORMALIZATION=true
  LABEL=hh360-4000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh360-4000 FILE=histo360-4000 STRIDE=10000 FMT=%16.10f
ff360-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh360-4000 TEMP=360.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff360-4000 FILE=fes360-4000 STRIDE=10000 FMT=%16.10f

weights360-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=360.0 REWEIGHT_PRESSURE=301.10704285 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights360-5000
  NORMALIZATION=true
  LABEL=hh360-5000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh360-5000 FILE=histo360-5000 STRIDE=10000 FMT=%16.10f
ff360-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh360-5000 TEMP=360.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff360-5000 FILE=fes360-5000 STRIDE=10000 FMT=%16.10f

weights360-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=360.0 REWEIGHT_PRESSURE=361.32845142 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights360-6000
  NORMALIZATION=true
  LABEL=hh360-6000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh360-6000 FILE=histo360-6000 STRIDE=10000 FMT=%16.10f
ff360-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh360-6000 TEMP=360.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff360-6000 FILE=fes360-6000 STRIDE=10000 FMT=%16.10f

weights360-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=360.0 REWEIGHT_PRESSURE=421.54985999 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights360-7000
  NORMALIZATION=true
  LABEL=hh360-7000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh360-7000 FILE=histo360-7000 STRIDE=10000 FMT=%16.10f
ff360-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh360-7000 TEMP=360.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff360-7000 FILE=fes360-7000 STRIDE=10000 FMT=%16.10f

weights360-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=360.0 REWEIGHT_PRESSURE=481.77126856 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights360-8000
  NORMALIZATION=true
  LABEL=hh360-8000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh360-8000 FILE=histo360-8000 STRIDE=10000 FMT=%16.10f
ff360-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh360-8000 TEMP=360.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff360-8000 FILE=fes360-8000 STRIDE=10000 FMT=%16.10f

weights360-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=360.0 REWEIGHT_PRESSURE=541.9926771300001 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights360-9000
  NORMALIZATION=true
  LABEL=hh360-9000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh360-9000 FILE=histo360-9000 STRIDE=10000 FMT=%16.10f
ff360-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh360-9000 TEMP=360.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff360-9000 FILE=fes360-9000 STRIDE=10000 FMT=%16.10f

weights360-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=360.0 REWEIGHT_PRESSURE=602.2140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights360-10000
  NORMALIZATION=true
  LABEL=hh360-10000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh360-10000 FILE=histo360-10000 STRIDE=10000 FMT=%16.10f
ff360-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh360-10000 TEMP=360.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff360-10000 FILE=fes360-10000 STRIDE=10000 FMT=%16.10f

weights370-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=370.0 REWEIGHT_PRESSURE=0.0 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights370-0
  NORMALIZATION=true
  LABEL=hh370-0
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh370-0 FILE=histo370-0 STRIDE=10000 FMT=%16.10f
ff370-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh370-0 TEMP=370.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff370-0 FILE=fes370-0 STRIDE=10000 FMT=%16.10f

weights370-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=370.0 REWEIGHT_PRESSURE=60.22140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights370-1000
  NORMALIZATION=true
  LABEL=hh370-1000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh370-1000 FILE=histo370-1000 STRIDE=10000 FMT=%16.10f
ff370-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh370-1000 TEMP=370.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff370-1000 FILE=fes370-1000 STRIDE=10000 FMT=%16.10f

weights370-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=370.0 REWEIGHT_PRESSURE=120.44281714 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights370-2000
  NORMALIZATION=true
  LABEL=hh370-2000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh370-2000 FILE=histo370-2000 STRIDE=10000 FMT=%16.10f
ff370-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh370-2000 TEMP=370.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff370-2000 FILE=fes370-2000 STRIDE=10000 FMT=%16.10f

weights370-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=370.0 REWEIGHT_PRESSURE=180.66422571 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights370-3000
  NORMALIZATION=true
  LABEL=hh370-3000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh370-3000 FILE=histo370-3000 STRIDE=10000 FMT=%16.10f
ff370-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh370-3000 TEMP=370.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff370-3000 FILE=fes370-3000 STRIDE=10000 FMT=%16.10f

weights370-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=370.0 REWEIGHT_PRESSURE=240.88563428 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights370-4000
  NORMALIZATION=true
  LABEL=hh370-4000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh370-4000 FILE=histo370-4000 STRIDE=10000 FMT=%16.10f
ff370-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh370-4000 TEMP=370.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff370-4000 FILE=fes370-4000 STRIDE=10000 FMT=%16.10f

weights370-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=370.0 REWEIGHT_PRESSURE=301.10704285 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights370-5000
  NORMALIZATION=true
  LABEL=hh370-5000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh370-5000 FILE=histo370-5000 STRIDE=10000 FMT=%16.10f
ff370-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh370-5000 TEMP=370.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff370-5000 FILE=fes370-5000 STRIDE=10000 FMT=%16.10f

weights370-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=370.0 REWEIGHT_PRESSURE=361.32845142 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights370-6000
  NORMALIZATION=true
  LABEL=hh370-6000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh370-6000 FILE=histo370-6000 STRIDE=10000 FMT=%16.10f
ff370-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh370-6000 TEMP=370.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff370-6000 FILE=fes370-6000 STRIDE=10000 FMT=%16.10f

weights370-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=370.0 REWEIGHT_PRESSURE=421.54985999 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights370-7000
  NORMALIZATION=true
  LABEL=hh370-7000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh370-7000 FILE=histo370-7000 STRIDE=10000 FMT=%16.10f
ff370-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh370-7000 TEMP=370.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff370-7000 FILE=fes370-7000 STRIDE=10000 FMT=%16.10f

weights370-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=370.0 REWEIGHT_PRESSURE=481.77126856 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights370-8000
  NORMALIZATION=true
  LABEL=hh370-8000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh370-8000 FILE=histo370-8000 STRIDE=10000 FMT=%16.10f
ff370-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh370-8000 TEMP=370.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff370-8000 FILE=fes370-8000 STRIDE=10000 FMT=%16.10f

weights370-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=370.0 REWEIGHT_PRESSURE=541.9926771300001 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights370-9000
  NORMALIZATION=true
  LABEL=hh370-9000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh370-9000 FILE=histo370-9000 STRIDE=10000 FMT=%16.10f
ff370-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh370-9000 TEMP=370.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff370-9000 FILE=fes370-9000 STRIDE=10000 FMT=%16.10f

weights370-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=370.0 REWEIGHT_PRESSURE=602.2140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights370-10000
  NORMALIZATION=true
  LABEL=hh370-10000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh370-10000 FILE=histo370-10000 STRIDE=10000 FMT=%16.10f
ff370-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh370-10000 TEMP=370.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff370-10000 FILE=fes370-10000 STRIDE=10000 FMT=%16.10f

weights380-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=380.0 REWEIGHT_PRESSURE=0.0 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights380-0
  NORMALIZATION=true
  LABEL=hh380-0
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh380-0 FILE=histo380-0 STRIDE=10000 FMT=%16.10f
ff380-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh380-0 TEMP=380.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff380-0 FILE=fes380-0 STRIDE=10000 FMT=%16.10f

weights380-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=380.0 REWEIGHT_PRESSURE=60.22140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights380-1000
  NORMALIZATION=true
  LABEL=hh380-1000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh380-1000 FILE=histo380-1000 STRIDE=10000 FMT=%16.10f
ff380-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh380-1000 TEMP=380.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff380-1000 FILE=fes380-1000 STRIDE=10000 FMT=%16.10f

weights380-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=380.0 REWEIGHT_PRESSURE=120.44281714 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights380-2000
  NORMALIZATION=true
  LABEL=hh380-2000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh380-2000 FILE=histo380-2000 STRIDE=10000 FMT=%16.10f
ff380-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh380-2000 TEMP=380.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff380-2000 FILE=fes380-2000 STRIDE=10000 FMT=%16.10f

weights380-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=380.0 REWEIGHT_PRESSURE=180.66422571 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights380-3000
  NORMALIZATION=true
  LABEL=hh380-3000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh380-3000 FILE=histo380-3000 STRIDE=10000 FMT=%16.10f
ff380-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh380-3000 TEMP=380.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff380-3000 FILE=fes380-3000 STRIDE=10000 FMT=%16.10f

weights380-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=380.0 REWEIGHT_PRESSURE=240.88563428 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights380-4000
  NORMALIZATION=true
  LABEL=hh380-4000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh380-4000 FILE=histo380-4000 STRIDE=10000 FMT=%16.10f
ff380-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh380-4000 TEMP=380.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff380-4000 FILE=fes380-4000 STRIDE=10000 FMT=%16.10f

weights380-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=380.0 REWEIGHT_PRESSURE=301.10704285 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights380-5000
  NORMALIZATION=true
  LABEL=hh380-5000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh380-5000 FILE=histo380-5000 STRIDE=10000 FMT=%16.10f
ff380-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh380-5000 TEMP=380.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff380-5000 FILE=fes380-5000 STRIDE=10000 FMT=%16.10f

weights380-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=380.0 REWEIGHT_PRESSURE=361.32845142 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights380-6000
  NORMALIZATION=true
  LABEL=hh380-6000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh380-6000 FILE=histo380-6000 STRIDE=10000 FMT=%16.10f
ff380-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh380-6000 TEMP=380.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff380-6000 FILE=fes380-6000 STRIDE=10000 FMT=%16.10f

weights380-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=380.0 REWEIGHT_PRESSURE=421.54985999 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights380-7000
  NORMALIZATION=true
  LABEL=hh380-7000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh380-7000 FILE=histo380-7000 STRIDE=10000 FMT=%16.10f
ff380-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh380-7000 TEMP=380.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff380-7000 FILE=fes380-7000 STRIDE=10000 FMT=%16.10f

weights380-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=380.0 REWEIGHT_PRESSURE=481.77126856 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights380-8000
  NORMALIZATION=true
  LABEL=hh380-8000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh380-8000 FILE=histo380-8000 STRIDE=10000 FMT=%16.10f
ff380-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh380-8000 TEMP=380.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff380-8000 FILE=fes380-8000 STRIDE=10000 FMT=%16.10f

weights380-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=380.0 REWEIGHT_PRESSURE=541.9926771300001 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights380-9000
  NORMALIZATION=true
  LABEL=hh380-9000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh380-9000 FILE=histo380-9000 STRIDE=10000 FMT=%16.10f
ff380-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh380-9000 TEMP=380.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff380-9000 FILE=fes380-9000 STRIDE=10000 FMT=%16.10f

weights380-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=380.0 REWEIGHT_PRESSURE=602.2140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights380-10000
  NORMALIZATION=true
  LABEL=hh380-10000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh380-10000 FILE=histo380-10000 STRIDE=10000 FMT=%16.10f
ff380-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh380-10000 TEMP=380.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff380-10000 FILE=fes380-10000 STRIDE=10000 FMT=%16.10f

weights390-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=390.0 REWEIGHT_PRESSURE=0.0 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights390-0
  NORMALIZATION=true
  LABEL=hh390-0
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh390-0 FILE=histo390-0 STRIDE=10000 FMT=%16.10f
ff390-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh390-0 TEMP=390.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff390-0 FILE=fes390-0 STRIDE=10000 FMT=%16.10f

weights390-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=390.0 REWEIGHT_PRESSURE=60.22140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights390-1000
  NORMALIZATION=true
  LABEL=hh390-1000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh390-1000 FILE=histo390-1000 STRIDE=10000 FMT=%16.10f
ff390-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh390-1000 TEMP=390.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff390-1000 FILE=fes390-1000 STRIDE=10000 FMT=%16.10f

weights390-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=390.0 REWEIGHT_PRESSURE=120.44281714 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights390-2000
  NORMALIZATION=true
  LABEL=hh390-2000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh390-2000 FILE=histo390-2000 STRIDE=10000 FMT=%16.10f
ff390-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh390-2000 TEMP=390.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff390-2000 FILE=fes390-2000 STRIDE=10000 FMT=%16.10f

weights390-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=390.0 REWEIGHT_PRESSURE=180.66422571 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights390-3000
  NORMALIZATION=true
  LABEL=hh390-3000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh390-3000 FILE=histo390-3000 STRIDE=10000 FMT=%16.10f
ff390-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh390-3000 TEMP=390.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff390-3000 FILE=fes390-3000 STRIDE=10000 FMT=%16.10f

weights390-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=390.0 REWEIGHT_PRESSURE=240.88563428 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights390-4000
  NORMALIZATION=true
  LABEL=hh390-4000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh390-4000 FILE=histo390-4000 STRIDE=10000 FMT=%16.10f
ff390-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh390-4000 TEMP=390.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff390-4000 FILE=fes390-4000 STRIDE=10000 FMT=%16.10f

weights390-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=390.0 REWEIGHT_PRESSURE=301.10704285 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights390-5000
  NORMALIZATION=true
  LABEL=hh390-5000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh390-5000 FILE=histo390-5000 STRIDE=10000 FMT=%16.10f
ff390-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh390-5000 TEMP=390.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff390-5000 FILE=fes390-5000 STRIDE=10000 FMT=%16.10f

weights390-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=390.0 REWEIGHT_PRESSURE=361.32845142 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights390-6000
  NORMALIZATION=true
  LABEL=hh390-6000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh390-6000 FILE=histo390-6000 STRIDE=10000 FMT=%16.10f
ff390-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh390-6000 TEMP=390.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff390-6000 FILE=fes390-6000 STRIDE=10000 FMT=%16.10f

weights390-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=390.0 REWEIGHT_PRESSURE=421.54985999 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights390-7000
  NORMALIZATION=true
  LABEL=hh390-7000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh390-7000 FILE=histo390-7000 STRIDE=10000 FMT=%16.10f
ff390-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh390-7000 TEMP=390.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff390-7000 FILE=fes390-7000 STRIDE=10000 FMT=%16.10f

weights390-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=390.0 REWEIGHT_PRESSURE=481.77126856 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights390-8000
  NORMALIZATION=true
  LABEL=hh390-8000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh390-8000 FILE=histo390-8000 STRIDE=10000 FMT=%16.10f
ff390-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh390-8000 TEMP=390.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff390-8000 FILE=fes390-8000 STRIDE=10000 FMT=%16.10f

weights390-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=390.0 REWEIGHT_PRESSURE=541.9926771300001 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights390-9000
  NORMALIZATION=true
  LABEL=hh390-9000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh390-9000 FILE=histo390-9000 STRIDE=10000 FMT=%16.10f
ff390-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh390-9000 TEMP=390.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff390-9000 FILE=fes390-9000 STRIDE=10000 FMT=%16.10f

weights390-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=390.0 REWEIGHT_PRESSURE=602.2140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights390-10000
  NORMALIZATION=true
  LABEL=hh390-10000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh390-10000 FILE=histo390-10000 STRIDE=10000 FMT=%16.10f
ff390-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh390-10000 TEMP=390.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff390-10000 FILE=fes390-10000 STRIDE=10000 FMT=%16.10f

weights400-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=400.0 REWEIGHT_PRESSURE=0.0 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights400-0
  NORMALIZATION=true
  LABEL=hh400-0
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh400-0 FILE=histo400-0 STRIDE=10000 FMT=%16.10f
ff400-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh400-0 TEMP=400.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff400-0 FILE=fes400-0 STRIDE=10000 FMT=%16.10f

weights400-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=400.0 REWEIGHT_PRESSURE=60.22140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights400-1000
  NORMALIZATION=true
  LABEL=hh400-1000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh400-1000 FILE=histo400-1000 STRIDE=10000 FMT=%16.10f
ff400-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh400-1000 TEMP=400.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff400-1000 FILE=fes400-1000 STRIDE=10000 FMT=%16.10f

weights400-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=400.0 REWEIGHT_PRESSURE=120.44281714 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights400-2000
  NORMALIZATION=true
  LABEL=hh400-2000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh400-2000 FILE=histo400-2000 STRIDE=10000 FMT=%16.10f
ff400-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh400-2000 TEMP=400.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff400-2000 FILE=fes400-2000 STRIDE=10000 FMT=%16.10f

weights400-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=400.0 REWEIGHT_PRESSURE=180.66422571 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights400-3000
  NORMALIZATION=true
  LABEL=hh400-3000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh400-3000 FILE=histo400-3000 STRIDE=10000 FMT=%16.10f
ff400-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh400-3000 TEMP=400.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff400-3000 FILE=fes400-3000 STRIDE=10000 FMT=%16.10f

weights400-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=400.0 REWEIGHT_PRESSURE=240.88563428 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights400-4000
  NORMALIZATION=true
  LABEL=hh400-4000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh400-4000 FILE=histo400-4000 STRIDE=10000 FMT=%16.10f
ff400-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh400-4000 TEMP=400.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff400-4000 FILE=fes400-4000 STRIDE=10000 FMT=%16.10f

weights400-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=400.0 REWEIGHT_PRESSURE=301.10704285 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights400-5000
  NORMALIZATION=true
  LABEL=hh400-5000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh400-5000 FILE=histo400-5000 STRIDE=10000 FMT=%16.10f
ff400-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh400-5000 TEMP=400.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff400-5000 FILE=fes400-5000 STRIDE=10000 FMT=%16.10f

weights400-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=400.0 REWEIGHT_PRESSURE=361.32845142 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights400-6000
  NORMALIZATION=true
  LABEL=hh400-6000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh400-6000 FILE=histo400-6000 STRIDE=10000 FMT=%16.10f
ff400-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh400-6000 TEMP=400.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff400-6000 FILE=fes400-6000 STRIDE=10000 FMT=%16.10f

weights400-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=400.0 REWEIGHT_PRESSURE=421.54985999 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights400-7000
  NORMALIZATION=true
  LABEL=hh400-7000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh400-7000 FILE=histo400-7000 STRIDE=10000 FMT=%16.10f
ff400-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh400-7000 TEMP=400.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff400-7000 FILE=fes400-7000 STRIDE=10000 FMT=%16.10f

weights400-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=400.0 REWEIGHT_PRESSURE=481.77126856 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights400-8000
  NORMALIZATION=true
  LABEL=hh400-8000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh400-8000 FILE=histo400-8000 STRIDE=10000 FMT=%16.10f
ff400-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh400-8000 TEMP=400.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff400-8000 FILE=fes400-8000 STRIDE=10000 FMT=%16.10f

weights400-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=400.0 REWEIGHT_PRESSURE=541.9926771300001 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights400-9000
  NORMALIZATION=true
  LABEL=hh400-9000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh400-9000 FILE=histo400-9000 STRIDE=10000 FMT=%16.10f
ff400-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh400-9000 TEMP=400.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff400-9000 FILE=fes400-9000 STRIDE=10000 FMT=%16.10f

weights400-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=400.0 REWEIGHT_PRESSURE=602.2140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights400-10000
  NORMALIZATION=true
  LABEL=hh400-10000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh400-10000 FILE=histo400-10000 STRIDE=10000 FMT=%16.10f
ff400-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh400-10000 TEMP=400.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff400-10000 FILE=fes400-10000 STRIDE=10000 FMT=%16.10f

weights410-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=410.0 REWEIGHT_PRESSURE=0.0 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights410-0
  NORMALIZATION=true
  LABEL=hh410-0
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh410-0 FILE=histo410-0 STRIDE=10000 FMT=%16.10f
ff410-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh410-0 TEMP=410.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff410-0 FILE=fes410-0 STRIDE=10000 FMT=%16.10f

weights410-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=410.0 REWEIGHT_PRESSURE=60.22140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights410-1000
  NORMALIZATION=true
  LABEL=hh410-1000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh410-1000 FILE=histo410-1000 STRIDE=10000 FMT=%16.10f
ff410-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh410-1000 TEMP=410.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff410-1000 FILE=fes410-1000 STRIDE=10000 FMT=%16.10f

weights410-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=410.0 REWEIGHT_PRESSURE=120.44281714 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights410-2000
  NORMALIZATION=true
  LABEL=hh410-2000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh410-2000 FILE=histo410-2000 STRIDE=10000 FMT=%16.10f
ff410-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh410-2000 TEMP=410.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff410-2000 FILE=fes410-2000 STRIDE=10000 FMT=%16.10f

weights410-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=410.0 REWEIGHT_PRESSURE=180.66422571 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights410-3000
  NORMALIZATION=true
  LABEL=hh410-3000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh410-3000 FILE=histo410-3000 STRIDE=10000 FMT=%16.10f
ff410-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh410-3000 TEMP=410.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff410-3000 FILE=fes410-3000 STRIDE=10000 FMT=%16.10f

weights410-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=410.0 REWEIGHT_PRESSURE=240.88563428 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights410-4000
  NORMALIZATION=true
  LABEL=hh410-4000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh410-4000 FILE=histo410-4000 STRIDE=10000 FMT=%16.10f
ff410-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh410-4000 TEMP=410.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff410-4000 FILE=fes410-4000 STRIDE=10000 FMT=%16.10f

weights410-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=410.0 REWEIGHT_PRESSURE=301.10704285 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights410-5000
  NORMALIZATION=true
  LABEL=hh410-5000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh410-5000 FILE=histo410-5000 STRIDE=10000 FMT=%16.10f
ff410-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh410-5000 TEMP=410.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff410-5000 FILE=fes410-5000 STRIDE=10000 FMT=%16.10f

weights410-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=410.0 REWEIGHT_PRESSURE=361.32845142 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights410-6000
  NORMALIZATION=true
  LABEL=hh410-6000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh410-6000 FILE=histo410-6000 STRIDE=10000 FMT=%16.10f
ff410-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh410-6000 TEMP=410.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff410-6000 FILE=fes410-6000 STRIDE=10000 FMT=%16.10f

weights410-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=410.0 REWEIGHT_PRESSURE=421.54985999 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights410-7000
  NORMALIZATION=true
  LABEL=hh410-7000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh410-7000 FILE=histo410-7000 STRIDE=10000 FMT=%16.10f
ff410-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh410-7000 TEMP=410.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff410-7000 FILE=fes410-7000 STRIDE=10000 FMT=%16.10f

weights410-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=410.0 REWEIGHT_PRESSURE=481.77126856 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights410-8000
  NORMALIZATION=true
  LABEL=hh410-8000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh410-8000 FILE=histo410-8000 STRIDE=10000 FMT=%16.10f
ff410-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh410-8000 TEMP=410.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff410-8000 FILE=fes410-8000 STRIDE=10000 FMT=%16.10f

weights410-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=410.0 REWEIGHT_PRESSURE=541.9926771300001 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights410-9000
  NORMALIZATION=true
  LABEL=hh410-9000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh410-9000 FILE=histo410-9000 STRIDE=10000 FMT=%16.10f
ff410-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh410-9000 TEMP=410.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff410-9000 FILE=fes410-9000 STRIDE=10000 FMT=%16.10f

weights410-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=410.0 REWEIGHT_PRESSURE=602.2140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights410-10000
  NORMALIZATION=true
  LABEL=hh410-10000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh410-10000 FILE=histo410-10000 STRIDE=10000 FMT=%16.10f
ff410-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh410-10000 TEMP=410.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff410-10000 FILE=fes410-10000 STRIDE=10000 FMT=%16.10f

weights420-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=420.0 REWEIGHT_PRESSURE=0.0 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights420-0
  NORMALIZATION=true
  LABEL=hh420-0
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh420-0 FILE=histo420-0 STRIDE=10000 FMT=%16.10f
ff420-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh420-0 TEMP=420.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff420-0 FILE=fes420-0 STRIDE=10000 FMT=%16.10f

weights420-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=420.0 REWEIGHT_PRESSURE=60.22140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights420-1000
  NORMALIZATION=true
  LABEL=hh420-1000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh420-1000 FILE=histo420-1000 STRIDE=10000 FMT=%16.10f
ff420-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh420-1000 TEMP=420.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff420-1000 FILE=fes420-1000 STRIDE=10000 FMT=%16.10f

weights420-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=420.0 REWEIGHT_PRESSURE=120.44281714 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights420-2000
  NORMALIZATION=true
  LABEL=hh420-2000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh420-2000 FILE=histo420-2000 STRIDE=10000 FMT=%16.10f
ff420-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh420-2000 TEMP=420.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff420-2000 FILE=fes420-2000 STRIDE=10000 FMT=%16.10f

weights420-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=420.0 REWEIGHT_PRESSURE=180.66422571 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights420-3000
  NORMALIZATION=true
  LABEL=hh420-3000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh420-3000 FILE=histo420-3000 STRIDE=10000 FMT=%16.10f
ff420-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh420-3000 TEMP=420.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff420-3000 FILE=fes420-3000 STRIDE=10000 FMT=%16.10f

weights420-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=420.0 REWEIGHT_PRESSURE=240.88563428 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights420-4000
  NORMALIZATION=true
  LABEL=hh420-4000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh420-4000 FILE=histo420-4000 STRIDE=10000 FMT=%16.10f
ff420-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh420-4000 TEMP=420.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff420-4000 FILE=fes420-4000 STRIDE=10000 FMT=%16.10f

weights420-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=420.0 REWEIGHT_PRESSURE=301.10704285 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights420-5000
  NORMALIZATION=true
  LABEL=hh420-5000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh420-5000 FILE=histo420-5000 STRIDE=10000 FMT=%16.10f
ff420-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh420-5000 TEMP=420.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff420-5000 FILE=fes420-5000 STRIDE=10000 FMT=%16.10f

weights420-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=420.0 REWEIGHT_PRESSURE=361.32845142 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights420-6000
  NORMALIZATION=true
  LABEL=hh420-6000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh420-6000 FILE=histo420-6000 STRIDE=10000 FMT=%16.10f
ff420-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh420-6000 TEMP=420.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff420-6000 FILE=fes420-6000 STRIDE=10000 FMT=%16.10f

weights420-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=420.0 REWEIGHT_PRESSURE=421.54985999 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights420-7000
  NORMALIZATION=true
  LABEL=hh420-7000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh420-7000 FILE=histo420-7000 STRIDE=10000 FMT=%16.10f
ff420-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh420-7000 TEMP=420.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff420-7000 FILE=fes420-7000 STRIDE=10000 FMT=%16.10f

weights420-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=420.0 REWEIGHT_PRESSURE=481.77126856 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights420-8000
  NORMALIZATION=true
  LABEL=hh420-8000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh420-8000 FILE=histo420-8000 STRIDE=10000 FMT=%16.10f
ff420-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh420-8000 TEMP=420.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff420-8000 FILE=fes420-8000 STRIDE=10000 FMT=%16.10f

weights420-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=420.0 REWEIGHT_PRESSURE=541.9926771300001 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights420-9000
  NORMALIZATION=true
  LABEL=hh420-9000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh420-9000 FILE=histo420-9000 STRIDE=10000 FMT=%16.10f
ff420-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh420-9000 TEMP=420.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff420-9000 FILE=fes420-9000 STRIDE=10000 FMT=%16.10f

weights420-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=420.0 REWEIGHT_PRESSURE=602.2140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights420-10000
  NORMALIZATION=true
  LABEL=hh420-10000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh420-10000 FILE=histo420-10000 STRIDE=10000 FMT=%16.10f
ff420-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh420-10000 TEMP=420.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff420-10000 FILE=fes420-10000 STRIDE=10000 FMT=%16.10f

weights430-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=430.0 REWEIGHT_PRESSURE=0.0 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights430-0
  NORMALIZATION=true
  LABEL=hh430-0
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh430-0 FILE=histo430-0 STRIDE=10000 FMT=%16.10f
ff430-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh430-0 TEMP=430.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff430-0 FILE=fes430-0 STRIDE=10000 FMT=%16.10f

weights430-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=430.0 REWEIGHT_PRESSURE=60.22140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights430-1000
  NORMALIZATION=true
  LABEL=hh430-1000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh430-1000 FILE=histo430-1000 STRIDE=10000 FMT=%16.10f
ff430-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh430-1000 TEMP=430.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff430-1000 FILE=fes430-1000 STRIDE=10000 FMT=%16.10f

weights430-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=430.0 REWEIGHT_PRESSURE=120.44281714 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights430-2000
  NORMALIZATION=true
  LABEL=hh430-2000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh430-2000 FILE=histo430-2000 STRIDE=10000 FMT=%16.10f
ff430-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh430-2000 TEMP=430.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff430-2000 FILE=fes430-2000 STRIDE=10000 FMT=%16.10f

weights430-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=430.0 REWEIGHT_PRESSURE=180.66422571 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights430-3000
  NORMALIZATION=true
  LABEL=hh430-3000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh430-3000 FILE=histo430-3000 STRIDE=10000 FMT=%16.10f
ff430-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh430-3000 TEMP=430.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff430-3000 FILE=fes430-3000 STRIDE=10000 FMT=%16.10f

weights430-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=430.0 REWEIGHT_PRESSURE=240.88563428 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights430-4000
  NORMALIZATION=true
  LABEL=hh430-4000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh430-4000 FILE=histo430-4000 STRIDE=10000 FMT=%16.10f
ff430-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh430-4000 TEMP=430.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff430-4000 FILE=fes430-4000 STRIDE=10000 FMT=%16.10f

weights430-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=430.0 REWEIGHT_PRESSURE=301.10704285 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights430-5000
  NORMALIZATION=true
  LABEL=hh430-5000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh430-5000 FILE=histo430-5000 STRIDE=10000 FMT=%16.10f
ff430-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh430-5000 TEMP=430.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff430-5000 FILE=fes430-5000 STRIDE=10000 FMT=%16.10f

weights430-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=430.0 REWEIGHT_PRESSURE=361.32845142 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights430-6000
  NORMALIZATION=true
  LABEL=hh430-6000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh430-6000 FILE=histo430-6000 STRIDE=10000 FMT=%16.10f
ff430-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh430-6000 TEMP=430.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff430-6000 FILE=fes430-6000 STRIDE=10000 FMT=%16.10f

weights430-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=430.0 REWEIGHT_PRESSURE=421.54985999 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights430-7000
  NORMALIZATION=true
  LABEL=hh430-7000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh430-7000 FILE=histo430-7000 STRIDE=10000 FMT=%16.10f
ff430-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh430-7000 TEMP=430.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff430-7000 FILE=fes430-7000 STRIDE=10000 FMT=%16.10f

weights430-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=430.0 REWEIGHT_PRESSURE=481.77126856 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights430-8000
  NORMALIZATION=true
  LABEL=hh430-8000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh430-8000 FILE=histo430-8000 STRIDE=10000 FMT=%16.10f
ff430-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh430-8000 TEMP=430.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff430-8000 FILE=fes430-8000 STRIDE=10000 FMT=%16.10f

weights430-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=430.0 REWEIGHT_PRESSURE=541.9926771300001 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights430-9000
  NORMALIZATION=true
  LABEL=hh430-9000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh430-9000 FILE=histo430-9000 STRIDE=10000 FMT=%16.10f
ff430-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh430-9000 TEMP=430.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff430-9000 FILE=fes430-9000 STRIDE=10000 FMT=%16.10f

weights430-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=430.0 REWEIGHT_PRESSURE=602.2140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights430-10000
  NORMALIZATION=true
  LABEL=hh430-10000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh430-10000 FILE=histo430-10000 STRIDE=10000 FMT=%16.10f
ff430-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh430-10000 TEMP=430.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff430-10000 FILE=fes430-10000 STRIDE=10000 FMT=%16.10f

weights440-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=440.0 REWEIGHT_PRESSURE=0.0 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights440-0
  NORMALIZATION=true
  LABEL=hh440-0
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh440-0 FILE=histo440-0 STRIDE=10000 FMT=%16.10f
ff440-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh440-0 TEMP=440.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff440-0 FILE=fes440-0 STRIDE=10000 FMT=%16.10f

weights440-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=440.0 REWEIGHT_PRESSURE=60.22140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights440-1000
  NORMALIZATION=true
  LABEL=hh440-1000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh440-1000 FILE=histo440-1000 STRIDE=10000 FMT=%16.10f
ff440-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh440-1000 TEMP=440.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff440-1000 FILE=fes440-1000 STRIDE=10000 FMT=%16.10f

weights440-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=440.0 REWEIGHT_PRESSURE=120.44281714 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights440-2000
  NORMALIZATION=true
  LABEL=hh440-2000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh440-2000 FILE=histo440-2000 STRIDE=10000 FMT=%16.10f
ff440-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh440-2000 TEMP=440.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff440-2000 FILE=fes440-2000 STRIDE=10000 FMT=%16.10f

weights440-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=440.0 REWEIGHT_PRESSURE=180.66422571 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights440-3000
  NORMALIZATION=true
  LABEL=hh440-3000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh440-3000 FILE=histo440-3000 STRIDE=10000 FMT=%16.10f
ff440-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh440-3000 TEMP=440.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff440-3000 FILE=fes440-3000 STRIDE=10000 FMT=%16.10f

weights440-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=440.0 REWEIGHT_PRESSURE=240.88563428 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights440-4000
  NORMALIZATION=true
  LABEL=hh440-4000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh440-4000 FILE=histo440-4000 STRIDE=10000 FMT=%16.10f
ff440-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh440-4000 TEMP=440.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff440-4000 FILE=fes440-4000 STRIDE=10000 FMT=%16.10f

weights440-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=440.0 REWEIGHT_PRESSURE=301.10704285 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights440-5000
  NORMALIZATION=true
  LABEL=hh440-5000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh440-5000 FILE=histo440-5000 STRIDE=10000 FMT=%16.10f
ff440-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh440-5000 TEMP=440.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff440-5000 FILE=fes440-5000 STRIDE=10000 FMT=%16.10f

weights440-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=440.0 REWEIGHT_PRESSURE=361.32845142 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights440-6000
  NORMALIZATION=true
  LABEL=hh440-6000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh440-6000 FILE=histo440-6000 STRIDE=10000 FMT=%16.10f
ff440-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh440-6000 TEMP=440.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff440-6000 FILE=fes440-6000 STRIDE=10000 FMT=%16.10f

weights440-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=440.0 REWEIGHT_PRESSURE=421.54985999 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights440-7000
  NORMALIZATION=true
  LABEL=hh440-7000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh440-7000 FILE=histo440-7000 STRIDE=10000 FMT=%16.10f
ff440-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh440-7000 TEMP=440.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff440-7000 FILE=fes440-7000 STRIDE=10000 FMT=%16.10f

weights440-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=440.0 REWEIGHT_PRESSURE=481.77126856 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights440-8000
  NORMALIZATION=true
  LABEL=hh440-8000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh440-8000 FILE=histo440-8000 STRIDE=10000 FMT=%16.10f
ff440-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh440-8000 TEMP=440.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff440-8000 FILE=fes440-8000 STRIDE=10000 FMT=%16.10f

weights440-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=440.0 REWEIGHT_PRESSURE=541.9926771300001 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights440-9000
  NORMALIZATION=true
  LABEL=hh440-9000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh440-9000 FILE=histo440-9000 STRIDE=10000 FMT=%16.10f
ff440-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh440-9000 TEMP=440.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff440-9000 FILE=fes440-9000 STRIDE=10000 FMT=%16.10f

weights440-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=440.0 REWEIGHT_PRESSURE=602.2140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights440-10000
  NORMALIZATION=true
  LABEL=hh440-10000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh440-10000 FILE=histo440-10000 STRIDE=10000 FMT=%16.10f
ff440-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh440-10000 TEMP=440.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff440-10000 FILE=fes440-10000 STRIDE=10000 FMT=%16.10f

weights450-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=450.0 REWEIGHT_PRESSURE=0.0 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights450-0
  NORMALIZATION=true
  LABEL=hh450-0
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh450-0 FILE=histo450-0 STRIDE=10000 FMT=%16.10f
ff450-0: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh450-0 TEMP=450.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff450-0 FILE=fes450-0 STRIDE=10000 FMT=%16.10f

weights450-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=450.0 REWEIGHT_PRESSURE=60.22140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights450-1000
  NORMALIZATION=true
  LABEL=hh450-1000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh450-1000 FILE=histo450-1000 STRIDE=10000 FMT=%16.10f
ff450-1000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh450-1000 TEMP=450.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff450-1000 FILE=fes450-1000 STRIDE=10000 FMT=%16.10f

weights450-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=450.0 REWEIGHT_PRESSURE=120.44281714 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights450-2000
  NORMALIZATION=true
  LABEL=hh450-2000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh450-2000 FILE=histo450-2000 STRIDE=10000 FMT=%16.10f
ff450-2000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh450-2000 TEMP=450.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff450-2000 FILE=fes450-2000 STRIDE=10000 FMT=%16.10f

weights450-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=450.0 REWEIGHT_PRESSURE=180.66422571 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights450-3000
  NORMALIZATION=true
  LABEL=hh450-3000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh450-3000 FILE=histo450-3000 STRIDE=10000 FMT=%16.10f
ff450-3000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh450-3000 TEMP=450.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff450-3000 FILE=fes450-3000 STRIDE=10000 FMT=%16.10f

weights450-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=450.0 REWEIGHT_PRESSURE=240.88563428 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights450-4000
  NORMALIZATION=true
  LABEL=hh450-4000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh450-4000 FILE=histo450-4000 STRIDE=10000 FMT=%16.10f
ff450-4000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh450-4000 TEMP=450.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff450-4000 FILE=fes450-4000 STRIDE=10000 FMT=%16.10f

weights450-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=450.0 REWEIGHT_PRESSURE=301.10704285 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights450-5000
  NORMALIZATION=true
  LABEL=hh450-5000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh450-5000 FILE=histo450-5000 STRIDE=10000 FMT=%16.10f
ff450-5000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh450-5000 TEMP=450.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff450-5000 FILE=fes450-5000 STRIDE=10000 FMT=%16.10f

weights450-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=450.0 REWEIGHT_PRESSURE=361.32845142 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights450-6000
  NORMALIZATION=true
  LABEL=hh450-6000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh450-6000 FILE=histo450-6000 STRIDE=10000 FMT=%16.10f
ff450-6000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh450-6000 TEMP=450.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff450-6000 FILE=fes450-6000 STRIDE=10000 FMT=%16.10f

weights450-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=450.0 REWEIGHT_PRESSURE=421.54985999 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights450-7000
  NORMALIZATION=true
  LABEL=hh450-7000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh450-7000 FILE=histo450-7000 STRIDE=10000 FMT=%16.10f
ff450-7000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh450-7000 TEMP=450.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff450-7000 FILE=fes450-7000 STRIDE=10000 FMT=%16.10f

weights450-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=450.0 REWEIGHT_PRESSURE=481.77126856 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights450-8000
  NORMALIZATION=true
  LABEL=hh450-8000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh450-8000 FILE=histo450-8000 STRIDE=10000 FMT=%16.10f
ff450-8000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh450-8000 TEMP=450.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff450-8000 FILE=fes450-8000 STRIDE=10000 FMT=%16.10f

weights450-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=450.0 REWEIGHT_PRESSURE=541.9926771300001 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights450-9000
  NORMALIZATION=true
  LABEL=hh450-9000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh450-9000 FILE=histo450-9000 STRIDE=10000 FMT=%16.10f
ff450-9000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh450-9000 TEMP=450.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff450-9000 FILE=fes450-9000 STRIDE=10000 FMT=%16.10f

weights450-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_r_e_w_e_i_g_h_t__t_e_m_p__p_r_e_s_s.html">REWEIGHT_TEMP_PRESS</a> TEMP=400 PRESSURE=301.10704285 REWEIGHT_TEMP=450.0 REWEIGHT_PRESSURE=602.2140857 ENERGY=renergy VOLUME=vol
<a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a> ...
  ARG=refcv.morethan
  GRID_MIN=-0.5
  GRID_MAX=250.5
  GRID_BIN=1000
  BANDWIDTH=1.
  LOGWEIGHTS=weights,weights450-10000
  NORMALIZATION=true
  LABEL=hh450-10000
  CLEAR=10000
... <a href="https://plumed.github.io/doc-master/user-doc/html/_h_i_s_t_o_g_r_a_m.html">HISTOGRAM</a>

<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=hh450-10000 FILE=histo450-10000 STRIDE=10000 FMT=%16.10f
ff450-10000: <a href="https://plumed.github.io/doc-master/user-doc/html/_c_o_n_v_e_r_t__t_o__f_e_s.html">CONVERT_TO_FES</a> GRID=hh450-10000 TEMP=450.0
<a href="https://plumed.github.io/doc-master/user-doc/html/_d_u_m_p_g_r_i_d.html">DUMPGRID</a> GRID=ff450-10000 FILE=fes450-10000 STRIDE=10000 FMT=%16.10f


<a href="https://plumed.github.io/doc-master/user-doc/html/_p_r_i_n_t.html">PRINT</a> ARG=* FILE=COLVAR STRIDE=1 FMT=%16.10f
</pre>{% endraw %}
