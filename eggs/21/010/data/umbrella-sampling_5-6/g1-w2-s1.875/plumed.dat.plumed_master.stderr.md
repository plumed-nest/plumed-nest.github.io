**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w2-s1.875/plumed.dat   
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
[fv-az95-172:43487] *** Process received signal ***
[fv-az95-172:43487] Signal: Aborted (6)
[fv-az95-172:43487] Signal code:  (-6)
[fv-az95-172:43487] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6dd50f7210]
[fv-az95-172:43487] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f6dd50f718b]
[fv-az95-172:43487] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6dd50d6859]
[fv-az95-172:43487] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6dd535e911]
[fv-az95-172:43487] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6dd536a38c]
[fv-az95-172:43487] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6dd536a3f7]
[fv-az95-172:43487] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f6dd536a6fd]
[fv-az95-172:43487] [ 7] plumed_master(+0xf5b5)[0x55dda16b65b5]
[fv-az95-172:43487] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f6dd50d80b3]
[fv-az95-172:43487] [ 9] plumed_master(+0xf8be)[0x55dda16b68be]
[fv-az95-172:43487] *** End of error message ***
</pre>
{% endraw %}
