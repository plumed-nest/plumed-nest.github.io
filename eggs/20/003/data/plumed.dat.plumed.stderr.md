**Project ID:** [plumID:20.003]({{ '/' | absolute_url }}eggs/20/003/)  
Stderr for source:  plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
TD_TS-target-plumed2.6.cpp:23:32: fatal error: TargetDistribution.h: No such file or directory
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:942, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/travis/opt/lib/plumed" env PLUMED_HTMLDIR="/home/travis/opt/share/doc/plumed" env PLUMED_INCLUDEDIR="/home/travis/opt/include" env PLUMED_PROGRAM_NAME="plumed" env PLUMED_IS_INSTALLED="yes" "/home/travis/opt/lib/plumed"/scripts/mklib.sh TD_TS-target-plumed2.6.cpp

[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f8376c7b4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f8376c7b428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f8376c7d02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f83772b584d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f83772b36b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f83772b3701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f83772b3919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f8376c66830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10107] *** End of error message ***
</pre>
{% endraw %}
