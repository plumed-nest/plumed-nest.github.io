**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w26-s6.708/plumed.dat   
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
[fv-az95-172:37829] *** Process received signal ***
[fv-az95-172:37829] Signal: Aborted (6)
[fv-az95-172:37829] Signal code:  (-6)
[fv-az95-172:37829] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fba0dedb210]
[fv-az95-172:37829] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fba0dedb18b]
[fv-az95-172:37829] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fba0deba859]
[fv-az95-172:37829] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fba0e142911]
[fv-az95-172:37829] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fba0e14e38c]
[fv-az95-172:37829] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fba0e14e3f7]
[fv-az95-172:37829] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fba0e14e6a9]
[fv-az95-172:37829] [ 7] plumed(+0xf47d)[0x556bb67fc47d]
[fv-az95-172:37829] [ 8] plumed(+0x14004)[0x556bb6801004]
[fv-az95-172:37829] [ 9] plumed(+0xf698)[0x556bb67fc698]
[fv-az95-172:37829] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fba0debc0b3]
[fv-az95-172:37829] [11] plumed(+0xf76e)[0x556bb67fc76e]
[fv-az95-172:37829] *** End of error message ***
</pre>
{% endraw %}
