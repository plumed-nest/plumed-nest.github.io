**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:704, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONFUNCTION LABEL=dAB2 ARG=dAB IMPORT=pythonfunction FUNCTION=square PERIODIC=NO
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fdc9b61b4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fdc9b61b428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fdc9b61d02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fdc9bc5584d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fdc9bc536b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fdc9bc53701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7fdc9bc53969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fdc9b606830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11937] *** End of error message ***
</pre>
{% endraw %}