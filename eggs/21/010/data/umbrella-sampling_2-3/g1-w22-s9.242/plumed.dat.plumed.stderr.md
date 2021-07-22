**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w22-s9.242/plumed.dat   
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
[fv-az95-172:39183] *** Process received signal ***
[fv-az95-172:39183] Signal: Aborted (6)
[fv-az95-172:39183] Signal code:  (-6)
[fv-az95-172:39183] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc12840e210]
[fv-az95-172:39183] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc12840e18b]
[fv-az95-172:39183] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc1283ed859]
[fv-az95-172:39183] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc128675911]
[fv-az95-172:39183] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc12868138c]
[fv-az95-172:39183] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc1286813f7]
[fv-az95-172:39183] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc1286816a9]
[fv-az95-172:39183] [ 7] plumed(+0xf47d)[0x561f36b0f47d]
[fv-az95-172:39183] [ 8] plumed(+0x14004)[0x561f36b14004]
[fv-az95-172:39183] [ 9] plumed(+0xf698)[0x561f36b0f698]
[fv-az95-172:39183] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc1283ef0b3]
[fv-az95-172:39183] [11] plumed(+0xf76e)[0x561f36b0f76e]
[fv-az95-172:39183] *** End of error message ***
</pre>
{% endraw %}
