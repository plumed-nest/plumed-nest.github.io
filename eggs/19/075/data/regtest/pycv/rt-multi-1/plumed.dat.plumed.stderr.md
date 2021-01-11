**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
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
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f25b35114b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f25b3511428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f25b351302a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f25b3b4b84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f25b3b496b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f25b3b49701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f25b3b49919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f25b34fc830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11979] *** End of error message ***
</pre>
{% endraw %}
