**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  2_ala2/simulation/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: NN_VES LABEL=nn ARG=phi NODES=48,24,12 OPTIM=ADAM ACTIVATION=RELU GRID_MIN=-pi GRID_MAX=pi GRID_BIN=50 TEMP=300. AVE_STRIDE=500 PRINT_STRIDE=1000 TARGET_STRIDE=1 GAMMA=10 LRATE=0.001 TAU_KL=10000 DECAY=1000 ADAPTIVE_DECAY=0.5
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f792da484b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f792da48428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f792da4a02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f792e08284d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f792e0806b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f792e080701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f792e080919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f792da33830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13775] *** End of error message ***
</pre>
{% endraw %}
