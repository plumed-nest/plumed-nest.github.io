**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w25-s9.111/plumed.dat   
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
[fv-az95-172:41096] *** Process received signal ***
[fv-az95-172:41096] Signal: Aborted (6)
[fv-az95-172:41096] Signal code:  (-6)
[fv-az95-172:41096] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe3e3f2a210]
[fv-az95-172:41096] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe3e3f2a18b]
[fv-az95-172:41096] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe3e3f09859]
[fv-az95-172:41096] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe3e4191911]
[fv-az95-172:41096] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe3e419d38c]
[fv-az95-172:41096] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe3e419d3f7]
[fv-az95-172:41096] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fe3e419d6a9]
[fv-az95-172:41096] [ 7] plumed(+0xf47d)[0x558cb0be847d]
[fv-az95-172:41096] [ 8] plumed(+0x14004)[0x558cb0bed004]
[fv-az95-172:41096] [ 9] plumed(+0xf698)[0x558cb0be8698]
[fv-az95-172:41096] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe3e3f0b0b3]
[fv-az95-172:41096] [11] plumed(+0xf76e)[0x558cb0be876e]
[fv-az95-172:41096] *** End of error message ***
</pre>
{% endraw %}
