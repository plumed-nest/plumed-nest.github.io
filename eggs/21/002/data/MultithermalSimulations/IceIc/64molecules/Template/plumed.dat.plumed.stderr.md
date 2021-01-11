**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIc/64molecules/Template/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [ 0] terminate called after throwing an instance of '/lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f6f571554b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f6f57155428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [ 2] PLMD::Plumed::ExceptionError'
/lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f6f5715702a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [ 3]   what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=225 MIN_TEMP=100 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?/usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f6f5778f84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [ 4] 
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] *** Process received signal ***
/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f6f5778d6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] [ 0] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [ 5] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f85429614b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f8542961428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f6f5778d701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [ 6] [ 2] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f6f5778d919]
/lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f854296302a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] [ 3] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [ 7] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f8542f9b84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] [ 4] plumed[0x40ec85]
/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f8542f996b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [10] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] [ 5] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f6f57140830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] [11] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f8542f99701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] [ 6] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07746] *** End of error message ***
/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f8542f99919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f854294c830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07747] *** End of error message ***
</pre>
{% endraw %}
