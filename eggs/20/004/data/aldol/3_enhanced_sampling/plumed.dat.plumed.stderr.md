**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  aldol/3_enhanced_sampling/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
../../code/PytorchModel.cpp:22:22: fatal error: Function.h: No such file or directory
compilation terminated.
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:942, function void PLMD::PlumedMain::load(const string&)
+++ message follows +++
An error happened while executing command env PLUMED_ROOT="/home/travis/opt/lib/plumed" env PLUMED_HTMLDIR="/home/travis/opt/share/doc/plumed" env PLUMED_INCLUDEDIR="/home/travis/opt/include" env PLUMED_PROGRAM_NAME="plumed" env PLUMED_IS_INSTALLED="yes" "/home/travis/opt/lib/plumed"/scripts/mklib.sh ../../code/PytorchModel.cpp

[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7efc262f34b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7efc262f3428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7efc262f502a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7efc2692d84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7efc2692b6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7efc2692b701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7efc2692b919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7efc262de830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10077] *** End of error message ***
</pre>
{% endraw %}