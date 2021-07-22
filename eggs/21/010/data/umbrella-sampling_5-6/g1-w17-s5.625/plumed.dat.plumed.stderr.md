**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w17-s5.625/plumed.dat   
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
[fv-az95-172:43406] *** Process received signal ***
[fv-az95-172:43406] Signal: Aborted (6)
[fv-az95-172:43406] Signal code:  (-6)
[fv-az95-172:43406] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2718a2c210]
[fv-az95-172:43406] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2718a2c18b]
[fv-az95-172:43406] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2718a0b859]
[fv-az95-172:43406] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2718c93911]
[fv-az95-172:43406] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2718c9f38c]
[fv-az95-172:43406] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2718c9f3f7]
[fv-az95-172:43406] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f2718c9f6a9]
[fv-az95-172:43406] [ 7] plumed(+0xf47d)[0x55eb2242547d]
[fv-az95-172:43406] [ 8] plumed(+0x14004)[0x55eb2242a004]
[fv-az95-172:43406] [ 9] plumed(+0xf698)[0x55eb22425698]
[fv-az95-172:43406] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2718a0d0b3]
[fv-az95-172:43406] [11] plumed(+0xf76e)[0x55eb2242576e]
[fv-az95-172:43406] *** End of error message ***
</pre>
{% endraw %}
