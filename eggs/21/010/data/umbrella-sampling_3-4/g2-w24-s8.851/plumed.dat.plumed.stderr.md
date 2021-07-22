**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w24-s8.851/plumed.dat   
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
[fv-az95-172:41069] *** Process received signal ***
[fv-az95-172:41069] Signal: Aborted (6)
[fv-az95-172:41069] Signal code:  (-6)
[fv-az95-172:41069] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fd97d5c6210]
[fv-az95-172:41069] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fd97d5c618b]
[fv-az95-172:41069] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fd97d5a5859]
[fv-az95-172:41069] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fd97d82d911]
[fv-az95-172:41069] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fd97d83938c]
[fv-az95-172:41069] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fd97d8393f7]
[fv-az95-172:41069] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fd97d8396a9]
[fv-az95-172:41069] [ 7] plumed(+0xf47d)[0x55ae0fe6947d]
[fv-az95-172:41069] [ 8] plumed(+0x14004)[0x55ae0fe6e004]
[fv-az95-172:41069] [ 9] plumed(+0xf698)[0x55ae0fe69698]
[fv-az95-172:41069] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fd97d5a70b3]
[fv-az95-172:41069] [11] plumed(+0xf76e)[0x55ae0fe6976e]
[fv-az95-172:41069] *** End of error message ***
</pre>
{% endraw %}
