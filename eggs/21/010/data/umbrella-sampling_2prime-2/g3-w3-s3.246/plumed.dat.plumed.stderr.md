**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g3-w3-s3.246/plumed.dat   
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
[fv-az95-172:40386] *** Process received signal ***
[fv-az95-172:40386] Signal: Aborted (6)
[fv-az95-172:40386] Signal code:  (-6)
[fv-az95-172:40386] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f735d658210]
[fv-az95-172:40386] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f735d65818b]
[fv-az95-172:40386] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f735d637859]
[fv-az95-172:40386] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f735d8bf911]
[fv-az95-172:40386] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f735d8cb38c]
[fv-az95-172:40386] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f735d8cb3f7]
[fv-az95-172:40386] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f735d8cb6a9]
[fv-az95-172:40386] [ 7] plumed(+0xf47d)[0x55d849c3847d]
[fv-az95-172:40386] [ 8] plumed(+0x14004)[0x55d849c3d004]
[fv-az95-172:40386] [ 9] plumed(+0xf698)[0x55d849c38698]
[fv-az95-172:40386] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f735d6390b3]
[fv-az95-172:40386] [11] plumed(+0xf76e)[0x55d849c3876e]
[fv-az95-172:40386] *** End of error message ***
</pre>
{% endraw %}
