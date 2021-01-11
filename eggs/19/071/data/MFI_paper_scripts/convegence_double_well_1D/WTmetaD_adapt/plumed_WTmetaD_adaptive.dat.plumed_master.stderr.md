**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
(download [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fac8c09e4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fac8c09e428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fac8c0a002a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fac8c6d884d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fac8c6d66b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fac8c6d6701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7fac8c6d6969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fac8c089830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:12334] *** End of error message ***
</pre>
{% endraw %}
