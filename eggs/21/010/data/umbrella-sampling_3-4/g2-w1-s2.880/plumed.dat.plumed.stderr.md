**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w1-s2.880/plumed.dat   
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
[fv-az95-172:40679] *** Process received signal ***
[fv-az95-172:40679] Signal: Aborted (6)
[fv-az95-172:40679] Signal code:  (-6)
[fv-az95-172:40679] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9d02b08210]
[fv-az95-172:40679] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f9d02b0818b]
[fv-az95-172:40679] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f9d02ae7859]
[fv-az95-172:40679] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9d02d6f911]
[fv-az95-172:40679] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f9d02d7b38c]
[fv-az95-172:40679] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f9d02d7b3f7]
[fv-az95-172:40679] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f9d02d7b6a9]
[fv-az95-172:40679] [ 7] plumed(+0xf47d)[0x5591b882b47d]
[fv-az95-172:40679] [ 8] plumed(+0x14004)[0x5591b8830004]
[fv-az95-172:40679] [ 9] plumed(+0xf698)[0x5591b882b698]
[fv-az95-172:40679] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f9d02ae90b3]
[fv-az95-172:40679] [11] plumed(+0xf76e)[0x5591b882b76e]
[fv-az95-172:40679] *** End of error message ***
</pre>
{% endraw %}
