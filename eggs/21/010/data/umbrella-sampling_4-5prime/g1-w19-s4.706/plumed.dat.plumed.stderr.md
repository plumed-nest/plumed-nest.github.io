**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w19-s4.706/plumed.dat   
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
[fv-az95-172:41854] *** Process received signal ***
[fv-az95-172:41854] Signal: Aborted (6)
[fv-az95-172:41854] Signal code:  (-6)
[fv-az95-172:41854] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f8a72506210]
[fv-az95-172:41854] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f8a7250618b]
[fv-az95-172:41854] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f8a724e5859]
[fv-az95-172:41854] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f8a7276d911]
[fv-az95-172:41854] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f8a7277938c]
[fv-az95-172:41854] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f8a727793f7]
[fv-az95-172:41854] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f8a727796a9]
[fv-az95-172:41854] [ 7] plumed(+0xf47d)[0x55ede509047d]
[fv-az95-172:41854] [ 8] plumed(+0x14004)[0x55ede5095004]
[fv-az95-172:41854] [ 9] plumed(+0xf698)[0x55ede5090698]
[fv-az95-172:41854] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f8a724e70b3]
[fv-az95-172:41854] [11] plumed(+0xf76e)[0x55ede509076e]
[fv-az95-172:41854] *** End of error message ***
</pre>
{% endraw %}
