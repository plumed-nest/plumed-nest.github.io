**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,3,4 IMPORT=distcv FUNCTION=cv COMPONENTS=d12,d13
Maybe a missing space or a typo?
[fv-az95-172:59407] *** Process received signal ***
[fv-az95-172:59407] Signal: Aborted (6)
[fv-az95-172:59407] Signal code:  (-6)
[fv-az95-172:59407] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fefaef3d210]
[fv-az95-172:59407] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fefaef3d18b]
[fv-az95-172:59407] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fefaef1c859]
[fv-az95-172:59407] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fefaf1a4911]
[fv-az95-172:59407] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fefaf1b038c]
[fv-az95-172:59407] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fefaf1b03f7]
[fv-az95-172:59407] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fefaf1b06fd]
[fv-az95-172:59407] [ 7] plumed_master(+0xf5b5)[0x561f4d9015b5]
[fv-az95-172:59407] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fefaef1e0b3]
[fv-az95-172:59407] [ 9] plumed_master(+0xf8be)[0x561f4d9018be]
[fv-az95-172:59407] *** End of error message ***
</pre>
{% endraw %}
