**Project ID:** [plumID:19.004]({{ '/' | absolute_url }}eggs/19/004/)  
Stderr for source:  MI-UBQ/4REP/plumed_4REP.dat   
(download [zipped raw stdout](plumed_4REP.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.cb-.*)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fde5b29d4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fde5b29d428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fde5b29f02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fde5b8d784d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fde5b8d56b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fde5b8d5701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7fde5b8d5969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fde5b288830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16536] *** End of error message ***
</pre>
{% endraw %}