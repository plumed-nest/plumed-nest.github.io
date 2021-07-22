**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w20-s5.412/plumed.dat   
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
[fv-az95-172:37682] *** Process received signal ***
[fv-az95-172:37682] Signal: Aborted (6)
[fv-az95-172:37682] Signal code:  (-6)
[fv-az95-172:37682] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb95e4ea210]
[fv-az95-172:37682] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb95e4ea18b]
[fv-az95-172:37682] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb95e4c9859]
[fv-az95-172:37682] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb95e751911]
[fv-az95-172:37682] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb95e75d38c]
[fv-az95-172:37682] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb95e75d3f7]
[fv-az95-172:37682] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fb95e75d6a9]
[fv-az95-172:37682] [ 7] plumed(+0xf47d)[0x560d1f07d47d]
[fv-az95-172:37682] [ 8] plumed(+0x14004)[0x560d1f082004]
[fv-az95-172:37682] [ 9] plumed(+0xf698)[0x560d1f07d698]
[fv-az95-172:37682] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb95e4cb0b3]
[fv-az95-172:37682] [11] plumed(+0xf76e)[0x560d1f07d76e]
[fv-az95-172:37682] *** End of error message ***
</pre>
{% endraw %}
