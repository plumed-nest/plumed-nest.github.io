**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w48-s11.460/plumed.dat   
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
[fv-az95-172:38420] *** Process received signal ***
[fv-az95-172:38420] Signal: Aborted (6)
[fv-az95-172:38420] Signal code:  (-6)
[fv-az95-172:38420] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f07c42a3210]
[fv-az95-172:38420] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f07c42a318b]
[fv-az95-172:38420] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f07c4282859]
[fv-az95-172:38420] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f07c450a911]
[fv-az95-172:38420] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f07c451638c]
[fv-az95-172:38420] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f07c45163f7]
[fv-az95-172:38420] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f07c45166a9]
[fv-az95-172:38420] [ 7] plumed(+0xf47d)[0x5576f118b47d]
[fv-az95-172:38420] [ 8] plumed(+0x14004)[0x5576f1190004]
[fv-az95-172:38420] [ 9] plumed(+0xf698)[0x5576f118b698]
[fv-az95-172:38420] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f07c42840b3]
[fv-az95-172:38420] [11] plumed(+0xf76e)[0x5576f118b76e]
[fv-az95-172:38420] *** End of error message ***
</pre>
{% endraw %}
