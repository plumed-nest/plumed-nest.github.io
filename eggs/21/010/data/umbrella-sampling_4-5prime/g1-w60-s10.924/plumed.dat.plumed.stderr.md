**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w60-s10.924/plumed.dat   
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
[fv-az95-172:42989] *** Process received signal ***
[fv-az95-172:42989] Signal: Aborted (6)
[fv-az95-172:42989] Signal code:  (-6)
[fv-az95-172:42989] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0c3ce61210]
[fv-az95-172:42989] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0c3ce6118b]
[fv-az95-172:42989] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0c3ce40859]
[fv-az95-172:42989] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0c3d0c8911]
[fv-az95-172:42989] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0c3d0d438c]
[fv-az95-172:42989] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0c3d0d43f7]
[fv-az95-172:42989] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0c3d0d46a9]
[fv-az95-172:42989] [ 7] plumed(+0xf47d)[0x5654ea43147d]
[fv-az95-172:42989] [ 8] plumed(+0x14004)[0x5654ea436004]
[fv-az95-172:42989] [ 9] plumed(+0xf698)[0x5654ea431698]
[fv-az95-172:42989] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0c3ce420b3]
[fv-az95-172:42989] [11] plumed(+0xf76e)[0x5654ea43176e]
[fv-az95-172:42989] *** End of error message ***
</pre>
{% endraw %}
