**Project ID:** [plumID:20.012]({{ '/' | absolute_url }}eggs/20/012/)  
Stderr for source:  fun_metaD/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:704, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PROJECTION_ON_AXIS LABEL=pp AXIS_ATOMS=p1,p2_FS2 ATOM=lig
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f5c9005c4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f5c9005c428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f5c9005e02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f5c9069684d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f5c906946b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f5c90694701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f5c90694969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f5c90047830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09674] *** End of error message ***
</pre>
{% endraw %}
