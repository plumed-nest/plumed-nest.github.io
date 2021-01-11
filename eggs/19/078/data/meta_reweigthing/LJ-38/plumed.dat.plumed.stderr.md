**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action MATHEVAL with label ns : action nsa has no component named nsa (hint! the components in this actions are: )
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fe4e2af24b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fe4e2af2428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fe4e2af402a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fe4e312c84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fe4e312a6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fe4e312a701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fe4e312a919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fe4e2add830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10850] *** End of error message ***
</pre>
{% endraw %}
