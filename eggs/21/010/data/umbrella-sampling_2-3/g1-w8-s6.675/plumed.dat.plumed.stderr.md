**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w8-s6.675/plumed.dat   
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
[fv-az95-172:39427] *** Process received signal ***
[fv-az95-172:39427] Signal: Aborted (6)
[fv-az95-172:39427] Signal code:  (-6)
[fv-az95-172:39427] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0fd8953210]
[fv-az95-172:39427] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0fd895318b]
[fv-az95-172:39427] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0fd8932859]
[fv-az95-172:39427] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0fd8bba911]
[fv-az95-172:39427] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0fd8bc638c]
[fv-az95-172:39427] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0fd8bc63f7]
[fv-az95-172:39427] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0fd8bc66a9]
[fv-az95-172:39427] [ 7] plumed(+0xf47d)[0x5629bb99447d]
[fv-az95-172:39427] [ 8] plumed(+0x14004)[0x5629bb999004]
[fv-az95-172:39427] [ 9] plumed(+0xf698)[0x5629bb994698]
[fv-az95-172:39427] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0fd89340b3]
[fv-az95-172:39427] [11] plumed(+0xf76e)[0x5629bb99476e]
[fv-az95-172:39427] *** End of error message ***
</pre>
{% endraw %}
