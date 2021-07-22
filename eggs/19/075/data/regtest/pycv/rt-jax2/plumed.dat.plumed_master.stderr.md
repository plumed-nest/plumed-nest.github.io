**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4,3 IMPORT=jaxcv FUNCTION=cv1
Maybe a missing space or a typo?
[fv-az95-172:59359] *** Process received signal ***
[fv-az95-172:59359] Signal: Aborted (6)
[fv-az95-172:59359] Signal code:  (-6)
[fv-az95-172:59359] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4454ba7210]
[fv-az95-172:59359] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f4454ba718b]
[fv-az95-172:59359] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4454b86859]
[fv-az95-172:59359] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4454e0e911]
[fv-az95-172:59359] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f4454e1a38c]
[fv-az95-172:59359] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f4454e1a3f7]
[fv-az95-172:59359] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f4454e1a6fd]
[fv-az95-172:59359] [ 7] plumed_master(+0xf5b5)[0x560b840dc5b5]
[fv-az95-172:59359] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f4454b880b3]
[fv-az95-172:59359] [ 9] plumed_master(+0xf8be)[0x560b840dc8be]
[fv-az95-172:59359] *** End of error message ***
</pre>
{% endraw %}
