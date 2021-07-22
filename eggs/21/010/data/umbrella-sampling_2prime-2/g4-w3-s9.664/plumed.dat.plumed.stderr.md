**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g4-w3-s9.664/plumed.dat   
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
[fv-az95-172:40532] *** Process received signal ***
[fv-az95-172:40532] Signal: Aborted (6)
[fv-az95-172:40532] Signal code:  (-6)
[fv-az95-172:40532] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f06164e5210]
[fv-az95-172:40532] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f06164e518b]
[fv-az95-172:40532] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f06164c4859]
[fv-az95-172:40532] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f061674c911]
[fv-az95-172:40532] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f061675838c]
[fv-az95-172:40532] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f06167583f7]
[fv-az95-172:40532] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f06167586a9]
[fv-az95-172:40532] [ 7] plumed(+0xf47d)[0x55fb4a12947d]
[fv-az95-172:40532] [ 8] plumed(+0x14004)[0x55fb4a12e004]
[fv-az95-172:40532] [ 9] plumed(+0xf698)[0x55fb4a129698]
[fv-az95-172:40532] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f06164c60b3]
[fv-az95-172:40532] [11] plumed(+0xf76e)[0x55fb4a12976e]
[fv-az95-172:40532] *** End of error message ***
</pre>
{% endraw %}
