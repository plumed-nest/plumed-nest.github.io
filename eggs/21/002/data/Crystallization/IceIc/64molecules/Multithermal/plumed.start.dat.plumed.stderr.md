**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIc/64molecules/Multithermal/plumed.start.dat   
(download [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip))  
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f9bfac2f4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f9bfac2f428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f9bfac3102a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [ 3] terminate called after throwing an instance of '/usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f9bfb26984d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [ 4] PLMD::Plumed::ExceptionError/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f9bfb2676b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [ 5] '
/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f9bfb267701]
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] [ 0] [ 6] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f00729fe4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f9bfb267919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [10] [ 1] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f9bfac1a830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07537] *** End of error message ***
/lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f00729fe428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f0072a0002a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f007303884d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f00730366b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f0073036701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f0073036919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f00729e9830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07538] *** End of error message ***
</pre>
{% endraw %}
