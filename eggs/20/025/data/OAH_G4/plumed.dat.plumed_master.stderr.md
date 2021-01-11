**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAH_G4/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
../code/PytorchModel.cpp:22:22: fatal error: Function.h: No such file or directory
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:940, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/travis/opt/lib/plumed_master" env PLUMED_HTMLDIR="/home/travis/opt/share/doc/plumed_master" env PLUMED_INCLUDEDIR="/home/travis/opt/include" env PLUMED_PROGRAM_NAME="plumed_master" env PLUMED_IS_INSTALLED="yes" "/home/travis/opt/lib/plumed_master"/scripts/mklib.sh ../code/PytorchModel.cpp

[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fe71b1104b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fe71b110428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fe71b11202a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fe71b74a84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fe71b7486b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fe71b748701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7fe71b748969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fe71b0fb830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08856] *** End of error message ***
</pre>
{% endraw %}
