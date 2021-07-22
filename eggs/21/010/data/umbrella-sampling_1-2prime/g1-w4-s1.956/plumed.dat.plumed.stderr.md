**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w4-s1.956/plumed.dat   
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
[fv-az95-172:38196] *** Process received signal ***
[fv-az95-172:38196] Signal: Aborted (6)
[fv-az95-172:38196] Signal code:  (-6)
[fv-az95-172:38196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb46432c210]
[fv-az95-172:38196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb46432c18b]
[fv-az95-172:38196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb46430b859]
[fv-az95-172:38196] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb464593911]
[fv-az95-172:38196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb46459f38c]
[fv-az95-172:38196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb46459f3f7]
[fv-az95-172:38196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fb46459f6a9]
[fv-az95-172:38196] [ 7] plumed(+0xf47d)[0x55e45b81747d]
[fv-az95-172:38196] [ 8] plumed(+0x14004)[0x55e45b81c004]
[fv-az95-172:38196] [ 9] plumed(+0xf698)[0x55e45b817698]
[fv-az95-172:38196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb46430d0b3]
[fv-az95-172:38196] [11] plumed(+0xf76e)[0x55e45b81776e]
[fv-az95-172:38196] *** End of error message ***
</pre>
{% endraw %}
