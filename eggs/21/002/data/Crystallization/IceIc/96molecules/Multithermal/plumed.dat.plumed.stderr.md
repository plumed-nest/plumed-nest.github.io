**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIc/96molecules/Multithermal/plumed.dat   
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f788d9e74b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f788d9e7428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f788d9e902a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f788e02184d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f788e01f6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f788e01f701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f788e01f919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f788d9d2830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07554] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fadcf1ba4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fadcf1ba428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fadcf1bc02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fadcf7f484d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fadcf7f26b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fadcf7f2701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fadcf7f2919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fadcf1a5830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07555] *** End of error message ***
</pre>
{% endraw %}
