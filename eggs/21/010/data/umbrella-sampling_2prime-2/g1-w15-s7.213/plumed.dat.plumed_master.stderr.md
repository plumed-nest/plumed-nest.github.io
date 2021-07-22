**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w15-s7.213/plumed.dat   
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
[fv-az95-172:39807] *** Process received signal ***
[fv-az95-172:39807] Signal: Aborted (6)
[fv-az95-172:39807] Signal code:  (-6)
[fv-az95-172:39807] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fad7d1d5210]
[fv-az95-172:39807] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fad7d1d518b]
[fv-az95-172:39807] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fad7d1b4859]
[fv-az95-172:39807] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fad7d43c911]
[fv-az95-172:39807] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fad7d44838c]
[fv-az95-172:39807] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fad7d4483f7]
[fv-az95-172:39807] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fad7d4486fd]
[fv-az95-172:39807] [ 7] plumed_master(+0xf5b5)[0x5602700165b5]
[fv-az95-172:39807] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fad7d1b60b3]
[fv-az95-172:39807] [ 9] plumed_master(+0xf8be)[0x5602700168be]
[fv-az95-172:39807] *** End of error message ***
</pre>
{% endraw %}
