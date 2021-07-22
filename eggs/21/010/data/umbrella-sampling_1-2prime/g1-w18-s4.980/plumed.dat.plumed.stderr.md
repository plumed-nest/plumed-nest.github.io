**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w18-s4.980/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: HILLS RESTART HEIGHT 0.000 W_STRIDE 50
Maybe a missing space or a typo?
[fv-az95-172:37609] *** Process received signal ***
[fv-az95-172:37609] Signal: Aborted (6)
[fv-az95-172:37609] Signal code:  (-6)
[fv-az95-172:37609] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f94926d7210]
[fv-az95-172:37609] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f94926d718b]
[fv-az95-172:37609] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f94926b6859]
[fv-az95-172:37609] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f949293e911]
[fv-az95-172:37609] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f949294a38c]
[fv-az95-172:37609] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f949294a3f7]
[fv-az95-172:37609] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f949294a6a9]
[fv-az95-172:37609] [ 7] plumed(+0xf47d)[0x562e64aa547d]
[fv-az95-172:37609] [ 8] plumed(+0x14004)[0x562e64aaa004]
[fv-az95-172:37609] [ 9] plumed(+0xf698)[0x562e64aa5698]
[fv-az95-172:37609] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f94926b80b3]
[fv-az95-172:37609] [11] plumed(+0xf76e)[0x562e64aa576e]
[fv-az95-172:37609] *** End of error message ***
</pre>
{% endraw %}
