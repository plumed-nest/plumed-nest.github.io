**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONFUNCTION LABEL=cc1 ARG=t1,t2,t3 IMPORT=pythonfunction FUNCTION=cc1 PERIODIC=NO
Maybe a missing space or a typo?
[fv-az95-172:59310] *** Process received signal ***
[fv-az95-172:59310] Signal: Aborted (6)
[fv-az95-172:59310] Signal code:  (-6)
[fv-az95-172:59310] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2e3ea29210]
[fv-az95-172:59310] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2e3ea2918b]
[fv-az95-172:59310] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2e3ea08859]
[fv-az95-172:59310] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2e3ec90911]
[fv-az95-172:59310] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2e3ec9c38c]
[fv-az95-172:59310] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2e3ec9c3f7]
[fv-az95-172:59310] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f2e3ec9c6fd]
[fv-az95-172:59310] [ 7] plumed_master(+0xf5b5)[0x56553a1dc5b5]
[fv-az95-172:59310] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2e3ea0a0b3]
[fv-az95-172:59310] [ 9] plumed_master(+0xf8be)[0x56553a1dc8be]
[fv-az95-172:59310] *** End of error message ***
</pre>
{% endraw %}
