**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w31-s6.526/plumed.dat   
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
[fv-az95-172:42210] *** Process received signal ***
[fv-az95-172:42210] Signal: Aborted (6)
[fv-az95-172:42210] Signal code:  (-6)
[fv-az95-172:42210] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6c00b27210]
[fv-az95-172:42210] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f6c00b2718b]
[fv-az95-172:42210] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6c00b06859]
[fv-az95-172:42210] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6c00d8e911]
[fv-az95-172:42210] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6c00d9a38c]
[fv-az95-172:42210] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6c00d9a3f7]
[fv-az95-172:42210] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f6c00d9a6fd]
[fv-az95-172:42210] [ 7] plumed_master(+0xf5b5)[0x55b5aaa685b5]
[fv-az95-172:42210] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f6c00b080b3]
[fv-az95-172:42210] [ 9] plumed_master(+0xf8be)[0x55b5aaa688be]
[fv-az95-172:42210] *** End of error message ***
</pre>
{% endraw %}
