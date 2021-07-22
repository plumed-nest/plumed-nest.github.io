**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w18-s7.250/plumed.dat   
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
[fv-az95-172:44663] *** Process received signal ***
[fv-az95-172:44663] Signal: Aborted (6)
[fv-az95-172:44663] Signal code:  (-6)
[fv-az95-172:44663] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f63dded2210]
[fv-az95-172:44663] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f63dded218b]
[fv-az95-172:44663] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f63ddeb1859]
[fv-az95-172:44663] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f63de139911]
[fv-az95-172:44663] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f63de14538c]
[fv-az95-172:44663] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f63de1453f7]
[fv-az95-172:44663] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f63de1456a9]
[fv-az95-172:44663] [ 7] plumed(+0xf47d)[0x559c4a27847d]
[fv-az95-172:44663] [ 8] plumed(+0x14004)[0x559c4a27d004]
[fv-az95-172:44663] [ 9] plumed(+0xf698)[0x559c4a278698]
[fv-az95-172:44663] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f63ddeb30b3]
[fv-az95-172:44663] [11] plumed(+0xf76e)[0x559c4a27876e]
[fv-az95-172:44663] *** End of error message ***
</pre>
{% endraw %}
