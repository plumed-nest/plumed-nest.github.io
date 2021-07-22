**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g3-w1-s2.438/plumed.dat   
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
[fv-az95-172:44193] *** Process received signal ***
[fv-az95-172:44193] Signal: Aborted (6)
[fv-az95-172:44193] Signal code:  (-6)
[fv-az95-172:44193] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fae06ddc210]
[fv-az95-172:44193] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fae06ddc18b]
[fv-az95-172:44193] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fae06dbb859]
[fv-az95-172:44193] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fae07043911]
[fv-az95-172:44193] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fae0704f38c]
[fv-az95-172:44193] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fae0704f3f7]
[fv-az95-172:44193] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fae0704f6a9]
[fv-az95-172:44193] [ 7] plumed(+0xf47d)[0x55a4128a647d]
[fv-az95-172:44193] [ 8] plumed(+0x14004)[0x55a4128ab004]
[fv-az95-172:44193] [ 9] plumed(+0xf698)[0x55a4128a6698]
[fv-az95-172:44193] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fae06dbd0b3]
[fv-az95-172:44193] [11] plumed(+0xf76e)[0x55a4128a676e]
[fv-az95-172:44193] *** End of error message ***
</pre>
{% endraw %}
