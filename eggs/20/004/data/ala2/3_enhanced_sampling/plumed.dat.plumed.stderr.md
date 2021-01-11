**Project ID:** [plumID:20.004]({{ '/' | absolute_url }}eggs/20/004/)  
Stderr for source:  ala2/3_enhanced_sampling/plumed.dat   
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

[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f6d6ff334b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f6d6ff33428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f6d6ff3502a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f6d7056d84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f6d7056b6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f6d7056b701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f6d7056b919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f6d6ff1e830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:10052] *** End of error message ***
</pre>
{% endraw %}
