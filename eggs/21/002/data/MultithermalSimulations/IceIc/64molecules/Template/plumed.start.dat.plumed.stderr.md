**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIc/64molecules/Template/plumed.start.dat   
(download [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=225 MIN_TEMP=100 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f26ecf784b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f26ecf78428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f26ecf7a02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f26ed5b284d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f26ed5b06b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] [ 5] terminate called after throwing an instance of '/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f26ed5b0701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] [ 6] PLMD::Plumed::ExceptionError/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f26ed5b0919]
'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=225 MIN_TEMP=100 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [ 0] [ 7] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f3a17c084b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f3a17c08428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [ 2] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f3a17c0a02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [ 3] [ 8] plumed[0x40f082]
/usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f3a1824284d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [ 4] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] [ 9] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f3a182406b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [ 5] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f3a18240701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [ 6] [10] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f3a18240919]
/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f26ecf63830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07763] *** End of error message ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f3a17bf3830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07764] *** End of error message ***
</pre>
{% endraw %}
