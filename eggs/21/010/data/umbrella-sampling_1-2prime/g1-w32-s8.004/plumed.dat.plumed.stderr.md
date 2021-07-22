**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w32-s8.004/plumed.dat   
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
[fv-az95-172:38001] *** Process received signal ***
[fv-az95-172:38001] Signal: Aborted (6)
[fv-az95-172:38001] Signal code:  (-6)
[fv-az95-172:38001] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f50d4345210]
[fv-az95-172:38001] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f50d434518b]
[fv-az95-172:38001] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f50d4324859]
[fv-az95-172:38001] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f50d45ac911]
[fv-az95-172:38001] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f50d45b838c]
[fv-az95-172:38001] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f50d45b83f7]
[fv-az95-172:38001] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f50d45b86a9]
[fv-az95-172:38001] [ 7] plumed(+0xf47d)[0x55d5c741047d]
[fv-az95-172:38001] [ 8] plumed(+0x14004)[0x55d5c7415004]
[fv-az95-172:38001] [ 9] plumed(+0xf698)[0x55d5c7410698]
[fv-az95-172:38001] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f50d43260b3]
[fv-az95-172:38001] [11] plumed(+0xf76e)[0x55d5c741076e]
[fv-az95-172:38001] *** End of error message ***
</pre>
{% endraw %}
