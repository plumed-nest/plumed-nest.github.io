**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:704, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: HBOND_COORD SPECIES=2665-10353:4 HYDROGENS=2666-10354:4,2667-10355:4 RCUTOO=0.324 RCUTOH=0.25 ACUT=0.20pi LABEL=hb
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7faa740414b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7faa74041428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7faa7404302a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7faa7467b84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7faa746796b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7faa74679701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7faa74679969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7faa7402c830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:15254] *** End of error message ***
</pre>
{% endraw %}
