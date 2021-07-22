**Project ID:** [plumID:19.004]({{ '/' | absolute_url }}eggs/19/004/)  
Stderr for source:  MI-UBQ/16REP/plumed_16REP.dat   
(download [zipped raw stdout](plumed_16REP.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at ActionWithArguments.cpp:129, function void PLMD::ActionWithArguments::interpretArgumentList(const std::vector<std::__cxx11::basic_string<char> >&, std::vector<PLMD::Value*>&)
+++ message follows +++
There isn't any action matching your regex (cs\.cb-.*)
[fv-az95-172:72927] *** Process received signal ***
[fv-az95-172:72927] Signal: Aborted (6)
[fv-az95-172:72927] Signal code:  (-6)
[fv-az95-172:72927] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f987c146210]
[fv-az95-172:72927] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f987c14618b]
[fv-az95-172:72927] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f987c125859]
[fv-az95-172:72927] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f987c3ad911]
[fv-az95-172:72927] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f987c3b938c]
[fv-az95-172:72927] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f987c3b93f7]
[fv-az95-172:72927] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f987c3b96a9]
[fv-az95-172:72927] [ 7] plumed(+0xf47d)[0x5584239d947d]
[fv-az95-172:72927] [ 8] plumed(+0x14004)[0x5584239de004]
[fv-az95-172:72927] [ 9] plumed(+0xf698)[0x5584239d9698]
[fv-az95-172:72927] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f987c1270b3]
[fv-az95-172:72927] [11] plumed(+0xf76e)[0x5584239d976e]
[fv-az95-172:72927] *** End of error message ***
</pre>
{% endraw %}
