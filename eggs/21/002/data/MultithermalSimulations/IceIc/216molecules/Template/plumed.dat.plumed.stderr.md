**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIc/216molecules/Template/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f32cd5854b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f32cd585428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f32cd58702a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f32cdbbf84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f32cdbbd6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f32cdbbd701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f32cdbbd919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
[ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] [10]   what():  /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f32cd570830]

+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=305 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [ 0] [11] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f59ff2284b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [ 1] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07712] *** End of error message ***
/lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f59ff228428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f59ff22a02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f59ff86284d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f59ff8606b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f59ff860701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f59ff860919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f59ff213830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07713] *** End of error message ***
</pre>
{% endraw %}
