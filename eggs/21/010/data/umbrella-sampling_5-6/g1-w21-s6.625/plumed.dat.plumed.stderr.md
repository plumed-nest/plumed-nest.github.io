**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w21-s6.625/plumed.dat   
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
[fv-az95-172:43529] *** Process received signal ***
[fv-az95-172:43529] Signal: Aborted (6)
[fv-az95-172:43529] Signal code:  (-6)
[fv-az95-172:43529] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6eccada210]
[fv-az95-172:43529] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f6eccada18b]
[fv-az95-172:43529] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6eccab9859]
[fv-az95-172:43529] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6eccd41911]
[fv-az95-172:43529] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6eccd4d38c]
[fv-az95-172:43529] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6eccd4d3f7]
[fv-az95-172:43529] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f6eccd4d6a9]
[fv-az95-172:43529] [ 7] plumed(+0xf47d)[0x55e16c53347d]
[fv-az95-172:43529] [ 8] plumed(+0x14004)[0x55e16c538004]
[fv-az95-172:43529] [ 9] plumed(+0xf698)[0x55e16c533698]
[fv-az95-172:43529] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f6eccabb0b3]
[fv-az95-172:43529] [11] plumed(+0xf76e)[0x55e16c53376e]
[fv-az95-172:43529] *** End of error message ***
</pre>
{% endraw %}
