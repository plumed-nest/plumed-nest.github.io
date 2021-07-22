**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w20-s7.813/plumed.dat   
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
[fv-az95-172:40981] *** Process received signal ***
[fv-az95-172:40981] Signal: Aborted (6)
[fv-az95-172:40981] Signal code:  (-6)
[fv-az95-172:40981] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f69435ac210]
[fv-az95-172:40981] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f69435ac18b]
[fv-az95-172:40981] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f694358b859]
[fv-az95-172:40981] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6943813911]
[fv-az95-172:40981] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f694381f38c]
[fv-az95-172:40981] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f694381f3f7]
[fv-az95-172:40981] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f694381f6fd]
[fv-az95-172:40981] [ 7] plumed_master(+0xf5b5)[0x55b0fceb85b5]
[fv-az95-172:40981] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f694358d0b3]
[fv-az95-172:40981] [ 9] plumed_master(+0xf8be)[0x55b0fceb88be]
[fv-az95-172:40981] *** End of error message ***
</pre>
{% endraw %}
