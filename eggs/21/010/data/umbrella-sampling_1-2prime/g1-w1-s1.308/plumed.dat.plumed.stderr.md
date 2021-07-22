**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w1-s1.308/plumed.dat   
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
[fv-az95-172:37386] *** Process received signal ***
[fv-az95-172:37386] Signal: Aborted (6)
[fv-az95-172:37386] Signal code:  (-6)
[fv-az95-172:37386] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fbfeaa89210]
[fv-az95-172:37386] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fbfeaa8918b]
[fv-az95-172:37386] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fbfeaa68859]
[fv-az95-172:37386] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fbfeacf0911]
[fv-az95-172:37386] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fbfeacfc38c]
[fv-az95-172:37386] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fbfeacfc3f7]
[fv-az95-172:37386] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fbfeacfc6a9]
[fv-az95-172:37386] [ 7] plumed(+0xf47d)[0x5615484dd47d]
[fv-az95-172:37386] [ 8] plumed(+0x14004)[0x5615484e2004]
[fv-az95-172:37386] [ 9] plumed(+0xf698)[0x5615484dd698]
[fv-az95-172:37386] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fbfeaa6a0b3]
[fv-az95-172:37386] [11] plumed(+0xf76e)[0x5615484dd76e]
[fv-az95-172:37386] *** End of error message ***
</pre>
{% endraw %}
