**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w21-s5.628/plumed.dat   
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
[fv-az95-172:37714] *** Process received signal ***
[fv-az95-172:37714] Signal: Aborted (6)
[fv-az95-172:37714] Signal code:  (-6)
[fv-az95-172:37714] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f368e03b210]
[fv-az95-172:37714] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f368e03b18b]
[fv-az95-172:37714] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f368e01a859]
[fv-az95-172:37714] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f368e2a2911]
[fv-az95-172:37714] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f368e2ae38c]
[fv-az95-172:37714] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f368e2ae3f7]
[fv-az95-172:37714] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f368e2ae6fd]
[fv-az95-172:37714] [ 7] plumed_master(+0xf5b5)[0x557316c3e5b5]
[fv-az95-172:37714] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f368e01c0b3]
[fv-az95-172:37714] [ 9] plumed_master(+0xf8be)[0x557316c3e8be]
[fv-az95-172:37714] *** End of error message ***
</pre>
{% endraw %}
