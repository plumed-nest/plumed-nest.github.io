**Project ID:** [plumID:20.025]({{ '/' | absolute_url }}eggs/20/025/)  
Stderr for source:  OAH_G1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
../code/PytorchModel.cpp:22:22: fatal error: Function.h: No such file or directory
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:942, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/travis/opt/lib/plumed" env PLUMED_HTMLDIR="/home/travis/opt/share/doc/plumed" env PLUMED_INCLUDEDIR="/home/travis/opt/include" env PLUMED_PROGRAM_NAME="plumed" env PLUMED_IS_INSTALLED="yes" "/home/travis/opt/lib/plumed"/scripts/mklib.sh ../code/PytorchModel.cpp

[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f71d0c074b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f71d0c07428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f71d0c0902a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f71d124184d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f71d123f6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f71d123f701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f71d123f919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f71d0bf2830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:08770] *** End of error message ***
</pre>
{% endraw %}
