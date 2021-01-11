**Project ID:** [plumID:20.022]({{ '/' | absolute_url }}eggs/20/022/)  
Stderr for source:  sodium/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_MULTITHERMAL_MULTIBARIC LABEL=mtp ARG=ene,vol TEMP=400 MIN_TEMP=350 MAX_TEMP=450 PRESSURE=0.06022140857*5000 MIN_PRESSURE=0 MAX_PRESSURE=0.06022140857*10000
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f70a59874b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f70a5987428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f70a598902a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f70a5fc184d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f70a5fbf6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f70a5fbf701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f70a5fbf919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f70a5972830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09276] *** End of error message ***
</pre>
{% endraw %}
