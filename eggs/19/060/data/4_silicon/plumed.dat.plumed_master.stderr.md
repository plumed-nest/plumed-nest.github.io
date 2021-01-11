**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  4_silicon/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:704, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: REFCV SPECIES=1-216 SIGMA=0.04 LATTICE_CONSTANTS=0.5431 CRYSTAL_STRUCTURE=DIAMOND LABEL=refcv MORE_THAN=RATIONAL R_0=0.5 NN=12 MM=24 MEAN
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f38780224b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f3878022428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f387802402a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f387865c84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f387865a6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f387865a701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f387865a969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f387800d830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13796] *** End of error message ***
</pre>
{% endraw %}
