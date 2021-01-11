**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  1_wolfe_quapp_potential/single_replica/inputs/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:704, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: NN_VES LABEL=nn ARG=p.x NODES=48,24,12 OPTIM=ADAM ACTIVATION=RELU GRID_MIN=-3. GRID_MAX=3. GRID_BIN=50 TEMP=1. AVE_STRIDE=500 PRINT_STRIDE=1000 TARGET_STRIDE=1 GAMMA=10 LRATE=0.001 TAU_KL=50000 DECAY=5000 ADAPTIVE_DECAY=0.5
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7efccd0c14b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7efccd0c1428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7efccd0c302a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7efccd6fb84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7efccd6f96b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7efccd6f9701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7efccd6f9969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7efccd0ac830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13769] *** End of error message ***
</pre>
{% endraw %}
