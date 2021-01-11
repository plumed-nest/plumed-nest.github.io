**Project ID:** [plumID:21.002]({{ '/' | absolute_url }}eggs/21/002/)  
Stderr for source:  Reweight/Example/NNP/plumed.dat   
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fdcecbcd4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fdcecbcd428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fdcecbcf02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=energy,vol TEMP=330 MIN_TEMP=300 MAX_TEMP=350 PRESSURE=0.06022140857 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] Signal code:  (-6)
[ 3] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7efc6620e4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7efc6620e428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7efc6621002a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fdced20784d]
/usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7efc6684884d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [ 4] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7efc668466b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7efc66846701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fdced2056b6]
/usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7efc66846919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [10] [travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7efc661f9830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07883] *** End of error message ***
[ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fdced205701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fdced205919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fdcecbb8830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07882] *** End of error message ***
</pre>
{% endraw %}
