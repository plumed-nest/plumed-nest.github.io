**Project ID:** [plumID:20.012]({{ '/' | absolute_url }}eggs/20/012/)  
Stderr for source:  fun_metaD/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PROJECTION_ON_AXIS LABEL=pp AXIS_ATOMS=p1,p2_FS2 ATOM=lig
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f7ee6f3b4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f7ee6f3b428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f7ee6f3d02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f7ee757584d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f7ee75736b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f7ee7573701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f7ee7573919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f7ee6f26830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09662] *** End of error message ***
</pre>
{% endraw %}
