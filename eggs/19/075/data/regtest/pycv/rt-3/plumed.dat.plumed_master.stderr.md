**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:704, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4 IMPORT=distcv FUNCTION=cv
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f44197674b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f4419767428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f441976902a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f4419da184d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f4419d9f6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f4419d9f701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f4419d9f969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f4419752830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11928] *** End of error message ***
</pre>
{% endraw %}