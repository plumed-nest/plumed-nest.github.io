**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIh/288molecules/Template/plumed.dat   
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f53b09db4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f53b09db428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f53b09dd02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f53b101584d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f53b10136b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f53b1013701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [ 6] terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=305 MIN_TEMP=260 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f53b1013919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [10] 
/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f53b09c6830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07814] *** End of error message ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f9e6ca564b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f9e6ca56428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f9e6ca5802a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f9e6d09084d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f9e6d08e6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f9e6d08e701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f9e6d08e919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f9e6ca41830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07815] *** End of error message ***
</pre>
{% endraw %}
