**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Crystallization/IceIc/96molecules/Multithermal/plumed.start.dat   
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f520483c4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f520483c428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f520483e02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f5204e7684d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f5204e746b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f5204e74701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f5204e74919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [10] terminate called after throwing an instance of '/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f5204827830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07571] *** End of error message ***
PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f8ac62d44b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f8ac62d4428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f8ac62d602a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f8ac690e84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f8ac690c6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f8ac690c701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f8ac690c919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f8ac62bf830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07572] *** End of error message ***
</pre>
{% endraw %}