**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIh/96molecules/Multithermal/plumed.start.dat   
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fe71a67b4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fe71a67b428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fe71a67d02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fe71acb584d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fe71acb36b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fe71acb3701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fe71acb3919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fe71a666830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07695] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f9feef4a4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f9feef4a428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f9feef4c02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f9fef58484d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f9fef5826b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f9fef582701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f9fef582919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f9feef35830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07696] *** End of error message ***
</pre>
{% endraw %}
