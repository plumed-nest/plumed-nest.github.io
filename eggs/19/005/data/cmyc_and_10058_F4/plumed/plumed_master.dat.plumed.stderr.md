**Project ID:** [plumID:19.005]({{ '/' | absolute_url }}eggs/19/005/)  
Stderr for source:  cmyc_and_10058_F4/plumed/plumed_master.dat   
(download [zipped raw stdout](plumed_master.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f650351f4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f650351f428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f650352102a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f6503b5984d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f6503b576b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f6503b57701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f6503b57919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f650350a830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16503] *** End of error message ***
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.ha_.*)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f7bcee4f4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f7bcee4f428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f7bcee5102a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f7bcf48984d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f7bcf4876b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f7bcf487701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f7bcf487919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f7bcee3a830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16502] *** End of error message ***
</pre>
{% endraw %}
