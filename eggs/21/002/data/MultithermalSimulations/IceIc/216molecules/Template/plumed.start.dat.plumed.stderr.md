**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIc/216molecules/Template/plumed.start.dat   
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f95cef9b4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f95cef9b428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f95cef9d02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f95cf5d584d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f95cf5d36b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f95cf5d3701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f95cf5d3919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f95cef86830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07730] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=305 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fc69e3d94b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fc69e3d9428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fc69e3db02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fc69ea1384d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fc69ea116b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fc69ea11701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fc69ea11919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fc69e3c4830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07729] *** End of error message ***
</pre>
{% endraw %}
