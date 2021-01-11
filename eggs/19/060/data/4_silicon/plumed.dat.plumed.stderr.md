**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  4_silicon/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: REFCV SPECIES=1-216 SIGMA=0.04 LATTICE_CONSTANTS=0.5431 CRYSTAL_STRUCTURE=DIAMOND LABEL=refcv MORE_THAN=RATIONAL R_0=0.5 NN=12 MM=24 MEAN
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f3490e644b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f3490e64428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f3490e6602a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f349149e84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f349149c6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f349149c701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f349149c919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f3490e4f830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:13793] *** End of error message ***
</pre>
{% endraw %}
