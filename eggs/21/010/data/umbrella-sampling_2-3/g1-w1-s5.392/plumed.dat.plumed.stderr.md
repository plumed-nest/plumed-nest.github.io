**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w1-s5.392/plumed.dat   
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
[fv-az95-172:38791] *** Process received signal ***
[fv-az95-172:38791] Signal: Aborted (6)
[fv-az95-172:38791] Signal code:  (-6)
[fv-az95-172:38791] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3a90314210]
[fv-az95-172:38791] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3a9031418b]
[fv-az95-172:38791] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3a902f3859]
[fv-az95-172:38791] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3a9057b911]
[fv-az95-172:38791] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f3a9058738c]
[fv-az95-172:38791] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f3a905873f7]
[fv-az95-172:38791] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f3a905876a9]
[fv-az95-172:38791] [ 7] plumed(+0xf47d)[0x55f0fe9dc47d]
[fv-az95-172:38791] [ 8] plumed(+0x14004)[0x55f0fe9e1004]
[fv-az95-172:38791] [ 9] plumed(+0xf698)[0x55f0fe9dc698]
[fv-az95-172:38791] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3a902f50b3]
[fv-az95-172:38791] [11] plumed(+0xf76e)[0x55f0fe9dc76e]
[fv-az95-172:38791] *** End of error message ***
</pre>
{% endraw %}
