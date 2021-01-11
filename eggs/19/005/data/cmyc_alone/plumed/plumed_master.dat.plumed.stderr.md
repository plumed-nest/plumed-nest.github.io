**Project ID:** [plumID:19.005]({{ '/' | absolute_url }}eggs/19/005/)  
Stderr for source:  cmyc_alone/plumed/plumed_master.dat   
(download [zipped raw stdout](plumed_master.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f58069f94b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f58069f9428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f58069fb02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f580703384d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f58070316b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f5807031701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f5807031919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f58069e4830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16483] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f27afb684b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f27afb68428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f27afb6a02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f27b01a284d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f27b01a06b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f27b01a0701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f27b01a0919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f27afb53830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16484] *** End of error message ***
</pre>
{% endraw %}
