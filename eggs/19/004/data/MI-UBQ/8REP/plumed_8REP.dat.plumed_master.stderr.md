**Project ID:** [plumID:19.004]({{ '/' | absolute_url }}eggs/19/004/)  
Stderr for source:  MI-UBQ/8REP/plumed_8REP.dat   
(download [zipped raw stdout](plumed_8REP.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.cb-.*)
[fv-az95-172:72984] *** Process received signal ***
[fv-az95-172:72984] Signal: Aborted (6)
[fv-az95-172:72984] Signal code:  (-6)
[fv-az95-172:72984] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa6a620b210]
[fv-az95-172:72984] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa6a620b18b]
[fv-az95-172:72984] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa6a61ea859]
[fv-az95-172:72984] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa6a6472911]
[fv-az95-172:72984] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa6a647e38c]
[fv-az95-172:72984] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa6a647e3f7]
[fv-az95-172:72984] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fa6a647e6fd]
[fv-az95-172:72984] [ 7] plumed_master(+0xf5b5)[0x55fcbb25f5b5]
[fv-az95-172:72984] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa6a61ec0b3]
[fv-az95-172:72984] [ 9] plumed_master(+0xf8be)[0x55fcbb25f8be]
[fv-az95-172:72984] *** End of error message ***
</pre>
{% endraw %}
