**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g4-w1-s6.29375/plumed.dat   
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
[fv-az95-172:45254] *** Process received signal ***
[fv-az95-172:45254] Signal: Aborted (6)
[fv-az95-172:45254] Signal code:  (-6)
[fv-az95-172:45254] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f7accbc7210]
[fv-az95-172:45254] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f7accbc718b]
[fv-az95-172:45254] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7accba6859]
[fv-az95-172:45254] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f7acce2e911]
[fv-az95-172:45254] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f7acce3a38c]
[fv-az95-172:45254] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f7acce3a3f7]
[fv-az95-172:45254] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f7acce3a6a9]
[fv-az95-172:45254] [ 7] plumed(+0xf47d)[0x558a6cf4d47d]
[fv-az95-172:45254] [ 8] plumed(+0x14004)[0x558a6cf52004]
[fv-az95-172:45254] [ 9] plumed(+0xf698)[0x558a6cf4d698]
[fv-az95-172:45254] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f7accba80b3]
[fv-az95-172:45254] [11] plumed(+0xf76e)[0x558a6cf4d76e]
[fv-az95-172:45254] *** End of error message ***
</pre>
{% endraw %}
