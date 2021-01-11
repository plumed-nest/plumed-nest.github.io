**Project ID:** [plumID:20.022]({{ '/' | absolute_url }}eggs/20/022/)  
Stderr for source:  alanine/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL LABEL=ecv ARG=ene MAX_TEMP=1000
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f0bd09124b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f0bd0912428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f0bd091402a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f0bd0f4c84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f0bd0f4a6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f0bd0f4a701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f0bd0f4a919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f0bd08fd830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09252] *** End of error message ***
</pre>
{% endraw %}
