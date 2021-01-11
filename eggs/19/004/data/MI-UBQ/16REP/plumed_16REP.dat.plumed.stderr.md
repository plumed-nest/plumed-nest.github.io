**Project ID:** [plumID:19.004]({{ '/' | absolute_url }}eggs/19/004/)  
Stderr for source:  MI-UBQ/16REP/plumed_16REP.dat   
(download [zipped raw stdout](plumed_16REP.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.cb-.*)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fd23be6d4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fd23be6d428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fd23be6f02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fd23c4a784d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fd23c4a56b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fd23c4a5701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fd23c4a5919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fd23be58830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:16524] *** End of error message ***
</pre>
{% endraw %}
