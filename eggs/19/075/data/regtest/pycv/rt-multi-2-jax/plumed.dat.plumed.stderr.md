**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-2-jax/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,3,4 IMPORT=distcv FUNCTION=cv COMPONENTS=d12,d13
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f8513e6f4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f8513e6f428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f8513e7102a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f85144a984d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f85144a76b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f85144a7701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f85144a7919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f8513e5a830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11988] *** End of error message ***
</pre>
{% endraw %}
