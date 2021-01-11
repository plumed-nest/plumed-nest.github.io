**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  MultithermalSimulations/IceIh/128molecules/Template/plumed.dat   
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fb352b034b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fb352b03428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fb352b0502a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fb35313d84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fb35313b6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fb35313b701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [ 6] terminate called after throwing an instance of '/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fb35313b919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [10] PLMD::Plumed::ExceptionError/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fb352aee830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07780] *** End of error message ***
'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=225 MIN_TEMP=100 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f3dbc0424b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f3dbc042428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f3dbc04402a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f3dbc67c84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f3dbc67a6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f3dbc67a701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f3dbc67a919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f3dbc02d830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07781] *** End of error message ***
</pre>
{% endraw %}
