**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w16-s4.251/plumed.dat   
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
[fv-az95-172:41780] *** Process received signal ***
[fv-az95-172:41780] Signal: Aborted (6)
[fv-az95-172:41780] Signal code:  (-6)
[fv-az95-172:41780] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5111f9d210]
[fv-az95-172:41780] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f5111f9d18b]
[fv-az95-172:41780] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5111f7c859]
[fv-az95-172:41780] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f5112204911]
[fv-az95-172:41780] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f511221038c]
[fv-az95-172:41780] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f51122103f7]
[fv-az95-172:41780] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f51122106a9]
[fv-az95-172:41780] [ 7] plumed(+0xf47d)[0x564e0845347d]
[fv-az95-172:41780] [ 8] plumed(+0x14004)[0x564e08458004]
[fv-az95-172:41780] [ 9] plumed(+0xf698)[0x564e08453698]
[fv-az95-172:41780] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f5111f7e0b3]
[fv-az95-172:41780] [11] plumed(+0xf76e)[0x564e0845376e]
[fv-az95-172:41780] *** End of error message ***
</pre>
{% endraw %}
