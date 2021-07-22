**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w36-s8.868/plumed.dat   
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
[fv-az95-172:38108] *** Process received signal ***
[fv-az95-172:38108] Signal: Aborted (6)
[fv-az95-172:38108] Signal code:  (-6)
[fv-az95-172:38108] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9420405210]
[fv-az95-172:38108] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f942040518b]
[fv-az95-172:38108] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f94203e4859]
[fv-az95-172:38108] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f942066c911]
[fv-az95-172:38108] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f942067838c]
[fv-az95-172:38108] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f94206783f7]
[fv-az95-172:38108] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f94206786fd]
[fv-az95-172:38108] [ 7] plumed_master(+0xf5b5)[0x5600f57ff5b5]
[fv-az95-172:38108] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f94203e60b3]
[fv-az95-172:38108] [ 9] plumed_master(+0xf8be)[0x5600f57ff8be]
[fv-az95-172:38108] *** End of error message ***
</pre>
{% endraw %}
