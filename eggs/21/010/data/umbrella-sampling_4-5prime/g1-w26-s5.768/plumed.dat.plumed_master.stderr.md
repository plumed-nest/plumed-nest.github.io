**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w26-s5.768/plumed.dat   
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
[fv-az95-172:42062] *** Process received signal ***
[fv-az95-172:42062] Signal: Aborted (6)
[fv-az95-172:42062] Signal code:  (-6)
[fv-az95-172:42062] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7faa6a4d3210]
[fv-az95-172:42062] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7faa6a4d318b]
[fv-az95-172:42062] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7faa6a4b2859]
[fv-az95-172:42062] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7faa6a73a911]
[fv-az95-172:42062] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7faa6a74638c]
[fv-az95-172:42062] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7faa6a7463f7]
[fv-az95-172:42062] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7faa6a7466fd]
[fv-az95-172:42062] [ 7] plumed_master(+0xf5b5)[0x5611900975b5]
[fv-az95-172:42062] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7faa6a4b40b3]
[fv-az95-172:42062] [ 9] plumed_master(+0xf8be)[0x5611900978be]
[fv-az95-172:42062] *** End of error message ***
</pre>
{% endraw %}
