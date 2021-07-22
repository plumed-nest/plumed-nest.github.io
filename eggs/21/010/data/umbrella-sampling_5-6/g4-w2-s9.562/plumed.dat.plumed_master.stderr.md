**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g4-w2-s9.562/plumed.dat   
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
[fv-az95-172:44274] *** Process received signal ***
[fv-az95-172:44274] Signal: Aborted (6)
[fv-az95-172:44274] Signal code:  (-6)
[fv-az95-172:44274] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2c0fbd4210]
[fv-az95-172:44274] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2c0fbd418b]
[fv-az95-172:44274] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2c0fbb3859]
[fv-az95-172:44274] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2c0fe3b911]
[fv-az95-172:44274] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2c0fe4738c]
[fv-az95-172:44274] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2c0fe473f7]
[fv-az95-172:44274] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f2c0fe476fd]
[fv-az95-172:44274] [ 7] plumed_master(+0xf5b5)[0x56070edb25b5]
[fv-az95-172:44274] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2c0fbb50b3]
[fv-az95-172:44274] [ 9] plumed_master(+0xf8be)[0x56070edb28be]
[fv-az95-172:44274] *** End of error message ***
</pre>
{% endraw %}
