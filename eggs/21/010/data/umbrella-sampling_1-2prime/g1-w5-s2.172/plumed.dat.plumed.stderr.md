**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w5-s2.172/plumed.dat   
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
[fv-az95-172:38468] *** Process received signal ***
[fv-az95-172:38468] Signal: Aborted (6)
[fv-az95-172:38468] Signal code:  (-6)
[fv-az95-172:38468] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6b41ac0210]
[fv-az95-172:38468] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f6b41ac018b]
[fv-az95-172:38468] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6b41a9f859]
[fv-az95-172:38468] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6b41d27911]
[fv-az95-172:38468] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6b41d3338c]
[fv-az95-172:38468] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6b41d333f7]
[fv-az95-172:38468] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f6b41d336a9]
[fv-az95-172:38468] [ 7] plumed(+0xf47d)[0x55928a5a647d]
[fv-az95-172:38468] [ 8] plumed(+0x14004)[0x55928a5ab004]
[fv-az95-172:38468] [ 9] plumed(+0xf698)[0x55928a5a6698]
[fv-az95-172:38468] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f6b41aa10b3]
[fv-az95-172:38468] [11] plumed(+0xf76e)[0x55928a5a676e]
[fv-az95-172:38468] *** End of error message ***
</pre>
{% endraw %}
