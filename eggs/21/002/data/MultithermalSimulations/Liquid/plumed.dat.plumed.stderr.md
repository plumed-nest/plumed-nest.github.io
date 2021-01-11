**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/Liquid/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] Signal code:  (-6)
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=350 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [ 0] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fa51bc294b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [ 1] [ 0] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fa51bc29428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fa51bc2b02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [ 3] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f199f8814b0]
/usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fa51c26384d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [ 4] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] [ 1] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fa51c2616b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [ 5] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f199f881428]
/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fa51c261701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [ 6] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] [ 2] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fa51c261919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fa51bc14830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07849] *** End of error message ***
/lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f199f88302a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f199febb84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f199feb96b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f199feb9701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f199feb9919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f199f86c830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07848] *** End of error message ***
</pre>
{% endraw %}
