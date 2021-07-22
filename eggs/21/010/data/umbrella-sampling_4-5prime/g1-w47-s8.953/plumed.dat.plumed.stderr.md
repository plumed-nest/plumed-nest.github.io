**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w47-s8.953/plumed.dat   
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
[fv-az95-172:42618] *** Process received signal ***
[fv-az95-172:42618] Signal: Aborted (6)
[fv-az95-172:42618] Signal code:  (-6)
[fv-az95-172:42618] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f50d599a210]
[fv-az95-172:42618] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f50d599a18b]
[fv-az95-172:42618] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f50d5979859]
[fv-az95-172:42618] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f50d5c01911]
[fv-az95-172:42618] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f50d5c0d38c]
[fv-az95-172:42618] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f50d5c0d3f7]
[fv-az95-172:42618] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f50d5c0d6a9]
[fv-az95-172:42618] [ 7] plumed(+0xf47d)[0x5595fe4e847d]
[fv-az95-172:42618] [ 8] plumed(+0x14004)[0x5595fe4ed004]
[fv-az95-172:42618] [ 9] plumed(+0xf698)[0x5595fe4e8698]
[fv-az95-172:42618] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f50d597b0b3]
[fv-az95-172:42618] [11] plumed(+0xf76e)[0x5595fe4e876e]
[fv-az95-172:42618] *** End of error message ***
</pre>
{% endraw %}
