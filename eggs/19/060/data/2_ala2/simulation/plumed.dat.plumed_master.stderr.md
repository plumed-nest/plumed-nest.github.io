**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  2_ala2/simulation/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:704, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: NN_VES LABEL=nn ARG=phi NODES=48,24,12 OPTIM=ADAM ACTIVATION=RELU GRID_MIN=-pi GRID_MAX=pi GRID_BIN=50 TEMP=300. AVE_STRIDE=500 PRINT_STRIDE=1000 TARGET_STRIDE=1 GAMMA=10 LRATE=0.001 TAU_KL=10000 DECAY=1000 ADAPTIVE_DECAY=0.5
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f3b52b744b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f3b52b74428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f3b52b7602a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f3b531ae84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f3b531ac6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f3b531ac701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f3b531ac969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f3b52b5f830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13778] *** End of error message ***
</pre>
{% endraw %}
