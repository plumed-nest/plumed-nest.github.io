**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:704, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONFUNCTION LABEL=cc1 ARG=t1,t2,t3 IMPORT=pythonfunction FUNCTION=cc1 PERIODIC=NO
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7ff754b024b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7ff754b02428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7ff754b0402a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7ff75513c84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7ff75513a6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7ff75513a701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7ff75513a969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7ff754aed830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11946] *** End of error message ***
</pre>
{% endraw %}
