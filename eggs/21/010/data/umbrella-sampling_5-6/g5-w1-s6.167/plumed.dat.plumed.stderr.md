**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g5-w1-s6.167/plumed.dat   
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
[fv-az95-172:44290] *** Process received signal ***
[fv-az95-172:44290] Signal: Aborted (6)
[fv-az95-172:44290] Signal code:  (-6)
[fv-az95-172:44290] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff0cf426210]
[fv-az95-172:44290] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff0cf42618b]
[fv-az95-172:44290] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff0cf405859]
[fv-az95-172:44290] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff0cf68d911]
[fv-az95-172:44290] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff0cf69938c]
[fv-az95-172:44290] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff0cf6993f7]
[fv-az95-172:44290] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ff0cf6996a9]
[fv-az95-172:44290] [ 7] plumed(+0xf47d)[0x5618d29c447d]
[fv-az95-172:44290] [ 8] plumed(+0x14004)[0x5618d29c9004]
[fv-az95-172:44290] [ 9] plumed(+0xf698)[0x5618d29c4698]
[fv-az95-172:44290] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff0cf4070b3]
[fv-az95-172:44290] [11] plumed(+0xf76e)[0x5618d29c476e]
[fv-az95-172:44290] *** End of error message ***
</pre>
{% endraw %}
