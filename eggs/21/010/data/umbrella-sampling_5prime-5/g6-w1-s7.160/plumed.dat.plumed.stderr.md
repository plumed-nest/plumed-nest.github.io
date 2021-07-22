**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g6-w1-s7.160/plumed.dat   
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
[fv-az95-172:45279] *** Process received signal ***
[fv-az95-172:45279] Signal: Aborted (6)
[fv-az95-172:45279] Signal code:  (-6)
[fv-az95-172:45279] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f16aee21210]
[fv-az95-172:45279] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f16aee2118b]
[fv-az95-172:45279] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f16aee00859]
[fv-az95-172:45279] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f16af088911]
[fv-az95-172:45279] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f16af09438c]
[fv-az95-172:45279] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f16af0943f7]
[fv-az95-172:45279] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f16af0946a9]
[fv-az95-172:45279] [ 7] plumed(+0xf47d)[0x5643b9d5d47d]
[fv-az95-172:45279] [ 8] plumed(+0x14004)[0x5643b9d62004]
[fv-az95-172:45279] [ 9] plumed(+0xf698)[0x5643b9d5d698]
[fv-az95-172:45279] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f16aee020b3]
[fv-az95-172:45279] [11] plumed(+0xf76e)[0x5643b9d5d76e]
[fv-az95-172:45279] *** End of error message ***
</pre>
{% endraw %}
