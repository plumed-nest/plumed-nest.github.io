**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  3_ala4/simulation/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: NN_VES TEMP=300.0 LABEL=bias ARG=phi1,phi2,phi3,psi1,psi2,psi3 NODES=96,48,24 OPTIM=ADAM ACTIVATION=RELU GRID_MIN=-pi,-pi,-pi,-pi,-pi,-pi GRID_MAX=pi,pi,pi,pi,pi,pi GRID_BIN=300,300,300,300,300,300 AVE_STRIDE=500 PRINT_STRIDE=100 TARGET_STRIDE=1 LRATE=0.001 GAMMA=10 TAU_KL=100000 MODE_DECAY=4 DECAY_STEP_START=10000 DECAY=2000 ADAPTIVE_DECAY=20 MC_POINTS=20000 MC_SIGMA=0.5,0.5,0.5,0.5,0.5,0.5 CALC_MC_ERR=0 MC_CONVERGENCE_TEST=0 L2_weight=0.2 SERIAL CALC_RCT
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fb22bafa4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fb22bafa428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fb22bafc02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fb22c13484d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fb22c1326b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fb22c132701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fb22c132919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fb22bae5830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13784] *** End of error message ***
</pre>
{% endraw %}
