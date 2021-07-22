**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w9-s6.858/plumed.dat   
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
[fv-az95-172:39453] *** Process received signal ***
[fv-az95-172:39453] Signal: Aborted (6)
[fv-az95-172:39453] Signal code:  (-6)
[fv-az95-172:39453] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa4f23cc210]
[fv-az95-172:39453] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa4f23cc18b]
[fv-az95-172:39453] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa4f23ab859]
[fv-az95-172:39453] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa4f2633911]
[fv-az95-172:39453] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa4f263f38c]
[fv-az95-172:39453] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa4f263f3f7]
[fv-az95-172:39453] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa4f263f6a9]
[fv-az95-172:39453] [ 7] plumed(+0xf47d)[0x5601df15347d]
[fv-az95-172:39453] [ 8] plumed(+0x14004)[0x5601df158004]
[fv-az95-172:39453] [ 9] plumed(+0xf698)[0x5601df153698]
[fv-az95-172:39453] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa4f23ad0b3]
[fv-az95-172:39453] [11] plumed(+0xf76e)[0x5601df15376e]
[fv-az95-172:39453] *** End of error message ***
</pre>
{% endraw %}
