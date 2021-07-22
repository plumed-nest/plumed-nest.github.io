**Project ID:** [plumID:19.004]({{ '/' | absolute_url }}eggs/19/004/)  
Stderr for source:  MI-UBQ/4REP/plumed_4REP.dat   
(download [zipped raw stdout](plumed_4REP.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.cb-.*)
[fv-az95-172:72951] *** Process received signal ***
[fv-az95-172:72951] Signal: Aborted (6)
[fv-az95-172:72951] Signal code:  (-6)
[fv-az95-172:72951] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff683ad2210]
[fv-az95-172:72951] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff683ad218b]
[fv-az95-172:72951] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff683ab1859]
[fv-az95-172:72951] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff683d39911]
[fv-az95-172:72951] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff683d4538c]
[fv-az95-172:72951] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff683d453f7]
[fv-az95-172:72951] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ff683d456a9]
[fv-az95-172:72951] [ 7] plumed(+0xf47d)[0x557c51bea47d]
[fv-az95-172:72951] [ 8] plumed(+0x14004)[0x557c51bef004]
[fv-az95-172:72951] [ 9] plumed(+0xf698)[0x557c51bea698]
[fv-az95-172:72951] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff683ab30b3]
[fv-az95-172:72951] [11] plumed(+0xf76e)[0x557c51bea76e]
[fv-az95-172:72951] *** End of error message ***
</pre>
{% endraw %}
