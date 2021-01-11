**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONFUNCTION LABEL=cc1 ARG=t1,t2,t3 IMPORT=pythonfunction FUNCTION=cc1 PERIODIC=NO
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fcb301164b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fcb30116428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fcb3011802a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fcb3075084d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fcb3074e6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fcb3074e701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fcb3074e919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fcb30101830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11943] *** End of error message ***
</pre>
{% endraw %}
