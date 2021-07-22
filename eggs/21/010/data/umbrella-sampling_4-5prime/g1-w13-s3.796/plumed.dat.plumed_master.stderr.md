**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w13-s3.796/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: HILLS RESTART HEIGHT 0.000 W_STRIDE 50
Maybe a missing space or a typo?
[fv-az95-172:41715] *** Process received signal ***
[fv-az95-172:41715] Signal: Aborted (6)
[fv-az95-172:41715] Signal code:  (-6)
[fv-az95-172:41715] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe9af4e4210]
[fv-az95-172:41715] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe9af4e418b]
[fv-az95-172:41715] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe9af4c3859]
[fv-az95-172:41715] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe9af74b911]
[fv-az95-172:41715] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe9af75738c]
[fv-az95-172:41715] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe9af7573f7]
[fv-az95-172:41715] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fe9af7576fd]
[fv-az95-172:41715] [ 7] plumed_master(+0xf5b5)[0x560aa0dc55b5]
[fv-az95-172:41715] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe9af4c50b3]
[fv-az95-172:41715] [ 9] plumed_master(+0xf8be)[0x560aa0dc58be]
[fv-az95-172:41715] *** End of error message ***
</pre>
{% endraw %}
