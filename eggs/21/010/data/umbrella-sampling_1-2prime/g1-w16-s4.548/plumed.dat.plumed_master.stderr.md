**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w16-s4.548/plumed.dat   
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
[fv-az95-172:37569] *** Process received signal ***
[fv-az95-172:37569] Signal: Aborted (6)
[fv-az95-172:37569] Signal code:  (-6)
[fv-az95-172:37569] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2f715da210]
[fv-az95-172:37569] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2f715da18b]
[fv-az95-172:37569] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2f715b9859]
[fv-az95-172:37569] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2f71841911]
[fv-az95-172:37569] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2f7184d38c]
[fv-az95-172:37569] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2f7184d3f7]
[fv-az95-172:37569] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f2f7184d6fd]
[fv-az95-172:37569] [ 7] plumed_master(+0xf5b5)[0x55fa7ef775b5]
[fv-az95-172:37569] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2f715bb0b3]
[fv-az95-172:37569] [ 9] plumed_master(+0xf8be)[0x55fa7ef778be]
[fv-az95-172:37569] *** End of error message ***
</pre>
{% endraw %}
