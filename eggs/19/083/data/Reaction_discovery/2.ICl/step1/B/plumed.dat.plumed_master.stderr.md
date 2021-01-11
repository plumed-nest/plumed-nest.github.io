**Project ID:** [plumID:19.083]({{ '/' | absolute_url }}eggs/19/083/)  
Stderr for source:  Reaction_discovery/2.ICl/step1/B/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action METAD with label restraint : restart file ..//HILLS.2 not found
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f7baa1ca4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f7baa1ca428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f7baa1cc02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f7baa80484d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f7baa8026b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f7baa802701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f7baa802969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f7baa1b5830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10212] *** End of error message ***
</pre>
{% endraw %}
