**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIh/96molecules/Multithermal/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fa3d68744b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fa3d6874428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fa3d687602a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fa3d6eae84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [ 4] terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f62534d34b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f62534d3428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f62534d502a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f6253b0d84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f6253b0b6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f6253b0b701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f6253b0b919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f62534be830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07679] *** End of error message ***
/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fa3d6eac6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fa3d6eac701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fa3d6eac919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fa3d685f830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07678] *** End of error message ***
</pre>
{% endraw %}
