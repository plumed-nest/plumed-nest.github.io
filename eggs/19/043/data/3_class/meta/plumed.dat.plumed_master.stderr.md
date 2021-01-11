**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f31515f14b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f31515f1428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f31515f302a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f3151c2b84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f3151c296b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f3151c29701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f3151c29969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f31515dc830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14676] *** End of error message ***
</pre>
{% endraw %}
