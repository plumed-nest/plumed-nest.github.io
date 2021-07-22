**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w33-s9.625/plumed.dat   
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
[fv-az95-172:43845] *** Process received signal ***
[fv-az95-172:43845] Signal: Aborted (6)
[fv-az95-172:43845] Signal code:  (-6)
[fv-az95-172:43845] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3ab7f53210]
[fv-az95-172:43845] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3ab7f5318b]
[fv-az95-172:43845] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3ab7f32859]
[fv-az95-172:43845] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3ab81ba911]
[fv-az95-172:43845] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f3ab81c638c]
[fv-az95-172:43845] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f3ab81c63f7]
[fv-az95-172:43845] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f3ab81c66a9]
[fv-az95-172:43845] [ 7] plumed(+0xf47d)[0x55ee7f9b047d]
[fv-az95-172:43845] [ 8] plumed(+0x14004)[0x55ee7f9b5004]
[fv-az95-172:43845] [ 9] plumed(+0xf698)[0x55ee7f9b0698]
[fv-az95-172:43845] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3ab7f340b3]
[fv-az95-172:43845] [11] plumed(+0xf76e)[0x55ee7f9b076e]
[fv-az95-172:43845] *** End of error message ***
</pre>
{% endraw %}
