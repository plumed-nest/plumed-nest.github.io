**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4 IMPORT=distcv FUNCTION=cv
Maybe a missing space or a typo?
[fv-az95-172:59252] *** Process received signal ***
[fv-az95-172:59252] Signal: Aborted (6)
[fv-az95-172:59252] Signal code:  (-6)
[fv-az95-172:59252] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9fb4bd3210]
[fv-az95-172:59252] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f9fb4bd318b]
[fv-az95-172:59252] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f9fb4bb2859]
[fv-az95-172:59252] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9fb4e3a911]
[fv-az95-172:59252] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f9fb4e4638c]
[fv-az95-172:59252] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f9fb4e463f7]
[fv-az95-172:59252] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f9fb4e466a9]
[fv-az95-172:59252] [ 7] plumed(+0xf47d)[0x55fcefc5047d]
[fv-az95-172:59252] [ 8] plumed(+0x14004)[0x55fcefc55004]
[fv-az95-172:59252] [ 9] plumed(+0xf698)[0x55fcefc50698]
[fv-az95-172:59252] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f9fb4bb40b3]
[fv-az95-172:59252] [11] plumed(+0xf76e)[0x55fcefc5076e]
[fv-az95-172:59252] *** End of error message ***
</pre>
{% endraw %}
