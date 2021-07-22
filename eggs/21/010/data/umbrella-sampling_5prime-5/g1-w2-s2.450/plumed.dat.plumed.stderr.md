**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w2-s2.450/plumed.dat   
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
[fv-az95-172:44712] *** Process received signal ***
[fv-az95-172:44712] Signal: Aborted (6)
[fv-az95-172:44712] Signal code:  (-6)
[fv-az95-172:44712] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4207351210]
[fv-az95-172:44712] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f420735118b]
[fv-az95-172:44712] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4207330859]
[fv-az95-172:44712] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f42075b8911]
[fv-az95-172:44712] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f42075c438c]
[fv-az95-172:44712] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f42075c43f7]
[fv-az95-172:44712] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f42075c46a9]
[fv-az95-172:44712] [ 7] plumed(+0xf47d)[0x55a9ee7cd47d]
[fv-az95-172:44712] [ 8] plumed(+0x14004)[0x55a9ee7d2004]
[fv-az95-172:44712] [ 9] plumed(+0xf698)[0x55a9ee7cd698]
[fv-az95-172:44712] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f42073320b3]
[fv-az95-172:44712] [11] plumed(+0xf76e)[0x55a9ee7cd76e]
[fv-az95-172:44712] *** End of error message ***
</pre>
{% endraw %}
