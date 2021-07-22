**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w21-s5.628/plumed.dat   
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
[fv-az95-172:37706] *** Process received signal ***
[fv-az95-172:37706] Signal: Aborted (6)
[fv-az95-172:37706] Signal code:  (-6)
[fv-az95-172:37706] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0d7dfd2210]
[fv-az95-172:37706] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0d7dfd218b]
[fv-az95-172:37706] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0d7dfb1859]
[fv-az95-172:37706] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0d7e239911]
[fv-az95-172:37706] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0d7e24538c]
[fv-az95-172:37706] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0d7e2453f7]
[fv-az95-172:37706] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0d7e2456a9]
[fv-az95-172:37706] [ 7] plumed(+0xf47d)[0x55f8a00c347d]
[fv-az95-172:37706] [ 8] plumed(+0x14004)[0x55f8a00c8004]
[fv-az95-172:37706] [ 9] plumed(+0xf698)[0x55f8a00c3698]
[fv-az95-172:37706] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0d7dfb30b3]
[fv-az95-172:37706] [11] plumed(+0xf76e)[0x55f8a00c376e]
[fv-az95-172:37706] *** End of error message ***
</pre>
{% endraw %}
