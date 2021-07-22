**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
(download [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATOMS141=9314,9319,9310,9313
Maybe a missing space or a typo?
[fv-az95-172:34786] *** Process received signal ***
[fv-az95-172:34786] Signal: Aborted (6)
[fv-az95-172:34786] Signal code:  (-6)
[fv-az95-172:34786] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2be6a7e210]
[fv-az95-172:34786] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2be6a7e18b]
[fv-az95-172:34786] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2be6a5d859]
[fv-az95-172:34786] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2be6ce5911]
[fv-az95-172:34786] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2be6cf138c]
[fv-az95-172:34786] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2be6cf13f7]
[fv-az95-172:34786] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f2be6cf16fd]
[fv-az95-172:34786] [ 7] plumed_master(+0xf5b5)[0x5647876545b5]
[fv-az95-172:34786] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2be6a5f0b3]
[fv-az95-172:34786] [ 9] plumed_master(+0xf8be)[0x5647876548be]
[fv-az95-172:34786] *** End of error message ***
</pre>
{% endraw %}
