**Project ID:** [plumID:19.005]({{ '/' | absolute_url }}eggs/19/005/)  
Stderr for source:  cmyc_and_10058_F4/plumed/plumed_master.dat   
(download [zipped raw stdout](plumed_master.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f81623914b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f8162391428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f816239302a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f81629cb84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f81629c96b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f81629c9701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f81629c9969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f816237c830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16510] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f4aa2b4f4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f4aa2b4f428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f4aa2b5102a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f4aa318984d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f4aa31876b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f4aa3187701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f4aa3187969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f4aa2b3a830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16511] *** End of error message ***
</pre>
{% endraw %}
