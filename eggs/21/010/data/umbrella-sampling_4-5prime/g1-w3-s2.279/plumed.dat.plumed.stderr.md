**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w3-s2.279/plumed.dat   
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
[fv-az95-172:42151] *** Process received signal ***
[fv-az95-172:42151] Signal: Aborted (6)
[fv-az95-172:42151] Signal code:  (-6)
[fv-az95-172:42151] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fcaea660210]
[fv-az95-172:42151] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fcaea66018b]
[fv-az95-172:42151] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fcaea63f859]
[fv-az95-172:42151] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fcaea8c7911]
[fv-az95-172:42151] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fcaea8d338c]
[fv-az95-172:42151] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fcaea8d33f7]
[fv-az95-172:42151] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fcaea8d36a9]
[fv-az95-172:42151] [ 7] plumed(+0xf47d)[0x55ed23b7b47d]
[fv-az95-172:42151] [ 8] plumed(+0x14004)[0x55ed23b80004]
[fv-az95-172:42151] [ 9] plumed(+0xf698)[0x55ed23b7b698]
[fv-az95-172:42151] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fcaea6410b3]
[fv-az95-172:42151] [11] plumed(+0xf76e)[0x55ed23b7b76e]
[fv-az95-172:42151] *** End of error message ***
</pre>
{% endraw %}
