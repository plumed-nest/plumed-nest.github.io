**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w17-s8.325/plumed.dat   
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
[fv-az95-172:38987] *** Process received signal ***
[fv-az95-172:38987] Signal: Aborted (6)
[fv-az95-172:38987] Signal code:  (-6)
[fv-az95-172:38987] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f49ecd53210]
[fv-az95-172:38987] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f49ecd5318b]
[fv-az95-172:38987] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f49ecd32859]
[fv-az95-172:38987] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f49ecfba911]
[fv-az95-172:38987] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f49ecfc638c]
[fv-az95-172:38987] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f49ecfc63f7]
[fv-az95-172:38987] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f49ecfc66a9]
[fv-az95-172:38987] [ 7] plumed(+0xf47d)[0x562fc108e47d]
[fv-az95-172:38987] [ 8] plumed(+0x14004)[0x562fc1093004]
[fv-az95-172:38987] [ 9] plumed(+0xf698)[0x562fc108e698]
[fv-az95-172:38987] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f49ecd340b3]
[fv-az95-172:38987] [11] plumed(+0xf76e)[0x562fc108e76e]
[fv-az95-172:38987] *** End of error message ***
</pre>
{% endraw %}
