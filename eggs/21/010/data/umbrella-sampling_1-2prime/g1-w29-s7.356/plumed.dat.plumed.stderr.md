**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w29-s7.356/plumed.dat   
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
[fv-az95-172:37902] *** Process received signal ***
[fv-az95-172:37902] Signal: Aborted (6)
[fv-az95-172:37902] Signal code:  (-6)
[fv-az95-172:37902] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa2c0aea210]
[fv-az95-172:37902] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa2c0aea18b]
[fv-az95-172:37902] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa2c0ac9859]
[fv-az95-172:37902] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa2c0d51911]
[fv-az95-172:37902] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa2c0d5d38c]
[fv-az95-172:37902] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa2c0d5d3f7]
[fv-az95-172:37902] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa2c0d5d6a9]
[fv-az95-172:37902] [ 7] plumed(+0xf47d)[0x55c7c977447d]
[fv-az95-172:37902] [ 8] plumed(+0x14004)[0x55c7c9779004]
[fv-az95-172:37902] [ 9] plumed(+0xf698)[0x55c7c9774698]
[fv-az95-172:37902] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa2c0acb0b3]
[fv-az95-172:37902] [11] plumed(+0xf76e)[0x55c7c977476e]
[fv-az95-172:37902] *** End of error message ***
</pre>
{% endraw %}
