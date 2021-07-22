**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w24-s6.276/plumed.dat   
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
[fv-az95-172:37781] *** Process received signal ***
[fv-az95-172:37781] Signal: Aborted (6)
[fv-az95-172:37781] Signal code:  (-6)
[fv-az95-172:37781] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe86f074210]
[fv-az95-172:37781] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe86f07418b]
[fv-az95-172:37781] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe86f053859]
[fv-az95-172:37781] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe86f2db911]
[fv-az95-172:37781] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe86f2e738c]
[fv-az95-172:37781] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe86f2e73f7]
[fv-az95-172:37781] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fe86f2e76a9]
[fv-az95-172:37781] [ 7] plumed(+0xf47d)[0x560e7c8a547d]
[fv-az95-172:37781] [ 8] plumed(+0x14004)[0x560e7c8aa004]
[fv-az95-172:37781] [ 9] plumed(+0xf698)[0x560e7c8a5698]
[fv-az95-172:37781] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe86f0550b3]
[fv-az95-172:37781] [11] plumed(+0xf76e)[0x560e7c8a576e]
[fv-az95-172:37781] *** End of error message ***
</pre>
{% endraw %}
