**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w21-s7.963/plumed.dat   
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
[fv-az95-172:39968] *** Process received signal ***
[fv-az95-172:39968] Signal: Aborted (6)
[fv-az95-172:39968] Signal code:  (-6)
[fv-az95-172:39968] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb31ee7a210]
[fv-az95-172:39968] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb31ee7a18b]
[fv-az95-172:39968] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb31ee59859]
[fv-az95-172:39968] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb31f0e1911]
[fv-az95-172:39968] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb31f0ed38c]
[fv-az95-172:39968] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb31f0ed3f7]
[fv-az95-172:39968] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fb31f0ed6a9]
[fv-az95-172:39968] [ 7] plumed(+0xf47d)[0x55cb4262347d]
[fv-az95-172:39968] [ 8] plumed(+0x14004)[0x55cb42628004]
[fv-az95-172:39968] [ 9] plumed(+0xf698)[0x55cb42623698]
[fv-az95-172:39968] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb31ee5b0b3]
[fv-az95-172:39968] [11] plumed(+0xf76e)[0x55cb4262376e]
[fv-az95-172:39968] *** End of error message ***
</pre>
{% endraw %}
