**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w32-s9.375/plumed.dat   
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
[fv-az95-172:43829] *** Process received signal ***
[fv-az95-172:43829] Signal: Aborted (6)
[fv-az95-172:43829] Signal code:  (-6)
[fv-az95-172:43829] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3096d46210]
[fv-az95-172:43829] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3096d4618b]
[fv-az95-172:43829] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3096d25859]
[fv-az95-172:43829] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3096fad911]
[fv-az95-172:43829] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f3096fb938c]
[fv-az95-172:43829] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f3096fb93f7]
[fv-az95-172:43829] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f3096fb96fd]
[fv-az95-172:43829] [ 7] plumed_master(+0xf5b5)[0x5617f81b55b5]
[fv-az95-172:43829] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3096d270b3]
[fv-az95-172:43829] [ 9] plumed_master(+0xf8be)[0x5617f81b58be]
[fv-az95-172:43829] *** End of error message ***
</pre>
{% endraw %}
