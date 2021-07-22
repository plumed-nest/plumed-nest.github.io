**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g2-w2-s4.987/plumed.dat   
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
[fv-az95-172:39527] *** Process received signal ***
[fv-az95-172:39527] Signal: Aborted (6)
[fv-az95-172:39527] Signal code:  (-6)
[fv-az95-172:39527] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6190871210]
[fv-az95-172:39527] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f619087118b]
[fv-az95-172:39527] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6190850859]
[fv-az95-172:39527] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6190ad8911]
[fv-az95-172:39527] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6190ae438c]
[fv-az95-172:39527] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6190ae43f7]
[fv-az95-172:39527] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f6190ae46a9]
[fv-az95-172:39527] [ 7] plumed(+0xf47d)[0x55bf513d547d]
[fv-az95-172:39527] [ 8] plumed(+0x14004)[0x55bf513da004]
[fv-az95-172:39527] [ 9] plumed(+0xf698)[0x55bf513d5698]
[fv-az95-172:39527] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f61908520b3]
[fv-az95-172:39527] [11] plumed(+0xf76e)[0x55bf513d576e]
[fv-az95-172:39527] *** End of error message ***
</pre>
{% endraw %}
