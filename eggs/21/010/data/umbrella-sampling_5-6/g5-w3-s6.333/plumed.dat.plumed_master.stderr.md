**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g5-w3-s6.333/plumed.dat   
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
[fv-az95-172:44347] *** Process received signal ***
[fv-az95-172:44347] Signal: Aborted (6)
[fv-az95-172:44347] Signal code:  (-6)
[fv-az95-172:44347] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f198a217210]
[fv-az95-172:44347] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f198a21718b]
[fv-az95-172:44347] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f198a1f6859]
[fv-az95-172:44347] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f198a47e911]
[fv-az95-172:44347] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f198a48a38c]
[fv-az95-172:44347] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f198a48a3f7]
[fv-az95-172:44347] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f198a48a6fd]
[fv-az95-172:44347] [ 7] plumed_master(+0xf5b5)[0x562891e295b5]
[fv-az95-172:44347] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f198a1f80b3]
[fv-az95-172:44347] [ 9] plumed_master(+0xf8be)[0x562891e298be]
[fv-az95-172:44347] *** End of error message ***
</pre>
{% endraw %}
