**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIc/64molecules/Multithermal/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionErrorterminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] Signal code:  (-6)
'
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] [ 0]   what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
/lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f0778b034b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] [ 0] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] [ 1] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f5f945d34b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f5f945d3428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f0778b03428]
/lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f5f945d502a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f0778b0502a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] [ 3] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f077913d84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f5f94c0d84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] [ 4] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f5f94c0b6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f077913b6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] [ 5] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f077913b701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f5f94c0b701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] [ 6] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f5f94c0b919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f077913b919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] [10] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f0778aee830]
plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f5f945be830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07521] *** End of error message ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07520] *** End of error message ***
</pre>
{% endraw %}
