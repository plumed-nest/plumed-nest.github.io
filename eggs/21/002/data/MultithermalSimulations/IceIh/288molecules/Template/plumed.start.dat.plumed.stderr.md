**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIh/288molecules/Template/plumed.start.dat   
(download [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=305 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f1c9939f4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f1c9939f428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f1c993a102a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f1c999d984d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f1c999d76b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [ 5] terminate called after throwing an instance of '/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f1c999d7701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [ 6] PLMD::Plumed::ExceptionError'
/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f1c999d7919]
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=305 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [ 7] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] *** Process received signal ***
plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f1c9938a830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [ 0] [11] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7ff988c674b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [ 1] plumed[0x40a0a9]
/lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7ff988c67428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [ 2] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07831] *** End of error message ***
/lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7ff988c6902a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7ff9892a184d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7ff98929f6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7ff98929f701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7ff98929f919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7ff988c52830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07832] *** End of error message ***
</pre>
{% endraw %}
