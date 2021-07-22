**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w35-s7.133/plumed.dat   
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
[fv-az95-172:42301] *** Process received signal ***
[fv-az95-172:42301] Signal: Aborted (6)
[fv-az95-172:42301] Signal code:  (-6)
[fv-az95-172:42301] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9fe9c89210]
[fv-az95-172:42301] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f9fe9c8918b]
[fv-az95-172:42301] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f9fe9c68859]
[fv-az95-172:42301] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9fe9ef0911]
[fv-az95-172:42301] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f9fe9efc38c]
[fv-az95-172:42301] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f9fe9efc3f7]
[fv-az95-172:42301] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f9fe9efc6a9]
[fv-az95-172:42301] [ 7] plumed(+0xf47d)[0x56173c39147d]
[fv-az95-172:42301] [ 8] plumed(+0x14004)[0x56173c396004]
[fv-az95-172:42301] [ 9] plumed(+0xf698)[0x56173c391698]
[fv-az95-172:42301] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f9fe9c6a0b3]
[fv-az95-172:42301] [11] plumed(+0xf76e)[0x56173c39176e]
[fv-az95-172:42301] *** End of error message ***
</pre>
{% endraw %}
