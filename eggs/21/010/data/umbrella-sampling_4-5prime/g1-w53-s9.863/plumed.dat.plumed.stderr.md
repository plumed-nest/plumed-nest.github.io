**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w53-s9.863/plumed.dat   
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
[fv-az95-172:42790] *** Process received signal ***
[fv-az95-172:42790] Signal: Aborted (6)
[fv-az95-172:42790] Signal code:  (-6)
[fv-az95-172:42790] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa6c2503210]
[fv-az95-172:42790] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa6c250318b]
[fv-az95-172:42790] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa6c24e2859]
[fv-az95-172:42790] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa6c276a911]
[fv-az95-172:42790] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa6c277638c]
[fv-az95-172:42790] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa6c27763f7]
[fv-az95-172:42790] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa6c27766a9]
[fv-az95-172:42790] [ 7] plumed(+0xf47d)[0x563bb708d47d]
[fv-az95-172:42790] [ 8] plumed(+0x14004)[0x563bb7092004]
[fv-az95-172:42790] [ 9] plumed(+0xf698)[0x563bb708d698]
[fv-az95-172:42790] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa6c24e40b3]
[fv-az95-172:42790] [11] plumed(+0xf76e)[0x563bb708d76e]
[fv-az95-172:42790] *** End of error message ***
</pre>
{% endraw %}
