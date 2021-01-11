**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4 IMPORT=pycv FUNCTION=cv1
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f56155274b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f5615527428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f561552902a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f5615b6184d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f5615b5f6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f5615b5f701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f5615b5f919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f5615512830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:11907] *** End of error message ***
</pre>
{% endraw %}
