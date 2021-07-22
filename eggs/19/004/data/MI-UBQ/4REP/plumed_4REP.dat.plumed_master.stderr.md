**Project ID:** [plumID:19.004]({{ '/' | absolute_url }}eggs/19/004/)  
Stderr for source:  MI-UBQ/4REP/plumed_4REP.dat   
(download [zipped raw stdout](plumed_4REP.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:128, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.cb-.*)
[fv-az95-172:72960] *** Process received signal ***
[fv-az95-172:72960] Signal: Aborted (6)
[fv-az95-172:72960] Signal code:  (-6)
[fv-az95-172:72960] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fbdee09f210]
[fv-az95-172:72960] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fbdee09f18b]
[fv-az95-172:72960] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fbdee07e859]
[fv-az95-172:72960] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fbdee306911]
[fv-az95-172:72960] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fbdee31238c]
[fv-az95-172:72960] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fbdee3123f7]
[fv-az95-172:72960] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fbdee3126fd]
[fv-az95-172:72960] [ 7] plumed_master(+0xf5b5)[0x56281582c5b5]
[fv-az95-172:72960] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fbdee0800b3]
[fv-az95-172:72960] [ 9] plumed_master(+0xf8be)[0x56281582c8be]
[fv-az95-172:72960] *** End of error message ***
</pre>
{% endraw %}
