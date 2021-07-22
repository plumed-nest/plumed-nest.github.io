**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w31-s9.125/plumed.dat   
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
[fv-az95-172:43797] *** Process received signal ***
[fv-az95-172:43797] Signal: Aborted (6)
[fv-az95-172:43797] Signal code:  (-6)
[fv-az95-172:43797] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f8c819f2210]
[fv-az95-172:43797] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f8c819f218b]
[fv-az95-172:43797] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f8c819d1859]
[fv-az95-172:43797] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f8c81c59911]
[fv-az95-172:43797] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f8c81c6538c]
[fv-az95-172:43797] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f8c81c653f7]
[fv-az95-172:43797] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f8c81c656a9]
[fv-az95-172:43797] [ 7] plumed(+0xf47d)[0x555620fa247d]
[fv-az95-172:43797] [ 8] plumed(+0x14004)[0x555620fa7004]
[fv-az95-172:43797] [ 9] plumed(+0xf698)[0x555620fa2698]
[fv-az95-172:43797] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f8c819d30b3]
[fv-az95-172:43797] [11] plumed(+0xf76e)[0x555620fa276e]
[fv-az95-172:43797] *** End of error message ***
</pre>
{% endraw %}
