**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
(download [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action MATHEVAL with label ns : action nsa has no component named nsa (hint! the components in this actions are: )
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f9b0216a4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f9b0216a428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f9b0216c02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f9b027a484d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f9b027a26b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f9b027a2701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f9b027a2969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f9b02155830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10862] *** End of error message ***
</pre>
{% endraw %}
