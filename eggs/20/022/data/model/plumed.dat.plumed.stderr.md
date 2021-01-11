**Project ID:** [plumID:20.022]({{ '/' | absolute_url }}eggs/20/022/)  
Stderr for source:  model/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_UMBRELLAS_LINE LABEL=ecv ARG=p.x MIN_CV=-2.5 MAX_CV=2.5 SIGMA=0.185815
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f21d980a4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f21d980a428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f21d980c02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f21d9e4484d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f21d9e426b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f21d9e42701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f21d9e42919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f21d97f5830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09268] *** End of error message ***
</pre>
{% endraw %}
