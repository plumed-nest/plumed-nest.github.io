**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w22-s5.844/plumed.dat   
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
[fv-az95-172:37730] *** Process received signal ***
[fv-az95-172:37730] Signal: Aborted (6)
[fv-az95-172:37730] Signal code:  (-6)
[fv-az95-172:37730] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3223f6e210]
[fv-az95-172:37730] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3223f6e18b]
[fv-az95-172:37730] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3223f4d859]
[fv-az95-172:37730] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f32241d5911]
[fv-az95-172:37730] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f32241e138c]
[fv-az95-172:37730] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f32241e13f7]
[fv-az95-172:37730] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f32241e16a9]
[fv-az95-172:37730] [ 7] plumed(+0xf47d)[0x558d6588047d]
[fv-az95-172:37730] [ 8] plumed(+0x14004)[0x558d65885004]
[fv-az95-172:37730] [ 9] plumed(+0xf698)[0x558d65880698]
[fv-az95-172:37730] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3223f4f0b3]
[fv-az95-172:37730] [11] plumed(+0xf76e)[0x558d6588076e]
[fv-az95-172:37730] *** End of error message ***
</pre>
{% endraw %}
