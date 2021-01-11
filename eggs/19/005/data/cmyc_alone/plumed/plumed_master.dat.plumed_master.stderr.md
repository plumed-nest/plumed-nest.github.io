**Project ID:** [plumID:19.005]({{ '/' | absolute_url }}eggs/19/005/)  
Stderr for source:  cmyc_alone/plumed/plumed_master.dat   
(download [zipped raw stdout](plumed_master.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fee231704b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fee23170428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fee2317202a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fee237aa84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fee237a86b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fee237a8701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7fee237a8969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fee2315b830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16491] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f73b3edc4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f73b3edc428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f73b3ede02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f73b451684d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f73b45146b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f73b4514701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f73b4514969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f73b3ec7830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16492] *** End of error message ***
</pre>
{% endraw %}
