**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w26-s9.370/plumed.dat   
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
[fv-az95-172:41120] *** Process received signal ***
[fv-az95-172:41120] Signal: Aborted (6)
[fv-az95-172:41120] Signal code:  (-6)
[fv-az95-172:41120] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0c546e3210]
[fv-az95-172:41120] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0c546e318b]
[fv-az95-172:41120] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0c546c2859]
[fv-az95-172:41120] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0c5494a911]
[fv-az95-172:41120] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0c5495638c]
[fv-az95-172:41120] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0c549563f7]
[fv-az95-172:41120] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0c549566a9]
[fv-az95-172:41120] [ 7] plumed(+0xf47d)[0x5573c852247d]
[fv-az95-172:41120] [ 8] plumed(+0x14004)[0x5573c8527004]
[fv-az95-172:41120] [ 9] plumed(+0xf698)[0x5573c8522698]
[fv-az95-172:41120] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0c546c40b3]
[fv-az95-172:41120] [11] plumed(+0xf76e)[0x5573c852276e]
[fv-az95-172:41120] *** End of error message ***
</pre>
{% endraw %}
