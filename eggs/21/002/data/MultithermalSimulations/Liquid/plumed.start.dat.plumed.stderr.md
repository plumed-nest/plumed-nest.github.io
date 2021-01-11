**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/Liquid/plumed.start.dat   
(download [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=350 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] *** Process received signal ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=350 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fe2674664b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fe267466428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [ 2] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fe26746802a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [ 3] [ 0] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fe267aa084d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [ 4] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f5988f604b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fe267a9e6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [ 5] [ 1] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fe267a9e701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [ 6] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f5988f60428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fe267a9e919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [10] [ 2] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fe267451830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07866] *** End of error message ***
/lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f5988f6202a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f598959a84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f59895986b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f5989598701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f5989598919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f5988f4b830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07865] *** End of error message ***
</pre>
{% endraw %}
