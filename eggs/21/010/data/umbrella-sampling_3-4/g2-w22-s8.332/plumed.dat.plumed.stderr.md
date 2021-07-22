**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w22-s8.332/plumed.dat   
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
[fv-az95-172:41021] *** Process received signal ***
[fv-az95-172:41021] Signal: Aborted (6)
[fv-az95-172:41021] Signal code:  (-6)
[fv-az95-172:41021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f044d46a210]
[fv-az95-172:41021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f044d46a18b]
[fv-az95-172:41021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f044d449859]
[fv-az95-172:41021] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f044d6d1911]
[fv-az95-172:41021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f044d6dd38c]
[fv-az95-172:41021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f044d6dd3f7]
[fv-az95-172:41021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f044d6dd6a9]
[fv-az95-172:41021] [ 7] plumed(+0xf47d)[0x558967f9247d]
[fv-az95-172:41021] [ 8] plumed(+0x14004)[0x558967f97004]
[fv-az95-172:41021] [ 9] plumed(+0xf698)[0x558967f92698]
[fv-az95-172:41021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f044d44b0b3]
[fv-az95-172:41021] [11] plumed(+0xf76e)[0x558967f9276e]
[fv-az95-172:41021] *** End of error message ***
</pre>
{% endraw %}
