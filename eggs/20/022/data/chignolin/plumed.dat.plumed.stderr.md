**Project ID:** [plumID:20.022]({{ '/' | absolute_url }}eggs/20/022/)  
Stderr for source:  chignolin/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=ecv ARG=ene,vol MIN_TEMP=270 MAX_TEMP=800 PRESSURE=0.06022140857*2000 MIN_PRESSURE=0.06022140857 MAX_PRESSURE=0.06022140857*4000 CUT_CORNER=500,0.06022140857,800,0.06022140857*1000
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fcedaf7e4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fcedaf7e428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fcedaf8002a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fcedb5b884d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fcedb5b66b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fcedb5b6701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fcedb5b6919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fcedaf69830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09260] *** End of error message ***
</pre>
{% endraw %}
