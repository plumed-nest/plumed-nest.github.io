**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w29-s7.356/plumed.dat   
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
[fv-az95-172:37910] *** Process received signal ***
[fv-az95-172:37910] Signal: Aborted (6)
[fv-az95-172:37910] Signal code:  (-6)
[fv-az95-172:37910] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe4dbd76210]
[fv-az95-172:37910] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe4dbd7618b]
[fv-az95-172:37910] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe4dbd55859]
[fv-az95-172:37910] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe4dbfdd911]
[fv-az95-172:37910] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe4dbfe938c]
[fv-az95-172:37910] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe4dbfe93f7]
[fv-az95-172:37910] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fe4dbfe96fd]
[fv-az95-172:37910] [ 7] plumed_master(+0xf5b5)[0x564266a2e5b5]
[fv-az95-172:37910] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe4dbd570b3]
[fv-az95-172:37910] [ 9] plumed_master(+0xf8be)[0x564266a2e8be]
[fv-az95-172:37910] *** End of error message ***
</pre>
{% endraw %}
