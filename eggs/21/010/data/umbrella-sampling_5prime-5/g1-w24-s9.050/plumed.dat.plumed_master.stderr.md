**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w24-s9.050/plumed.dat   
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
[fv-az95-172:44842] *** Process received signal ***
[fv-az95-172:44842] Signal: Aborted (6)
[fv-az95-172:44842] Signal code:  (-6)
[fv-az95-172:44842] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5f8a0dc210]
[fv-az95-172:44842] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f5f8a0dc18b]
[fv-az95-172:44842] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5f8a0bb859]
[fv-az95-172:44842] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f5f8a343911]
[fv-az95-172:44842] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f5f8a34f38c]
[fv-az95-172:44842] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f5f8a34f3f7]
[fv-az95-172:44842] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f5f8a34f6fd]
[fv-az95-172:44842] [ 7] plumed_master(+0xf5b5)[0x55f17302b5b5]
[fv-az95-172:44842] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f5f8a0bd0b3]
[fv-az95-172:44842] [ 9] plumed_master(+0xf8be)[0x55f17302b8be]
[fv-az95-172:44842] *** End of error message ***
</pre>
{% endraw %}
