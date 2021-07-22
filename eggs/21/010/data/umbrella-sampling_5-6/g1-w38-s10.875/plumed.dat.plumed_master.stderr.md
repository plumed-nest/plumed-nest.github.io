**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w38-s10.875/plumed.dat   
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
[fv-az95-172:43980] *** Process received signal ***
[fv-az95-172:43980] Signal: Aborted (6)
[fv-az95-172:43980] Signal code:  (-6)
[fv-az95-172:43980] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f205e6a0210]
[fv-az95-172:43980] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f205e6a018b]
[fv-az95-172:43980] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f205e67f859]
[fv-az95-172:43980] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f205e907911]
[fv-az95-172:43980] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f205e91338c]
[fv-az95-172:43980] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f205e9133f7]
[fv-az95-172:43980] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f205e9136fd]
[fv-az95-172:43980] [ 7] plumed_master(+0xf5b5)[0x563df07105b5]
[fv-az95-172:43980] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f205e6810b3]
[fv-az95-172:43980] [ 9] plumed_master(+0xf8be)[0x563df07108be]
[fv-az95-172:43980] *** End of error message ***
</pre>
{% endraw %}
