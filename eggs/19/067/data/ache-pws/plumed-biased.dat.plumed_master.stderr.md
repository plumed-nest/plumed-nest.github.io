**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
(download [zipped raw stdout](plumed-biased.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fe45ee524b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fe45ee52428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fe45ee5402a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fe45f48c84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fe45f48a6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fe45f48a701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7fe45f48a969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fe45ee3d830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12514] *** End of error message ***
</pre>
{% endraw %}
