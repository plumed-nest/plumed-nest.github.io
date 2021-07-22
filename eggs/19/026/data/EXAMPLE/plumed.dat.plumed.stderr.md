**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: HBOND_COORD SPECIES=2665-10353:4 HYDROGENS=2666-10354:4,2667-10355:4 RCUTOO=0.324 RCUTOH=0.25 ACUT=0.20pi LABEL=hb
Maybe a missing space or a typo?
[fv-az95-172:69187] *** Process received signal ***
[fv-az95-172:69187] Signal: Aborted (6)
[fv-az95-172:69187] Signal code:  (-6)
[fv-az95-172:69187] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fee3f99b210]
[fv-az95-172:69187] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fee3f99b18b]
[fv-az95-172:69187] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fee3f97a859]
[fv-az95-172:69187] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fee3fc02911]
[fv-az95-172:69187] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fee3fc0e38c]
[fv-az95-172:69187] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fee3fc0e3f7]
[fv-az95-172:69187] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fee3fc0e6a9]
[fv-az95-172:69187] [ 7] plumed(+0xf47d)[0x563630e9547d]
[fv-az95-172:69187] [ 8] plumed(+0x14004)[0x563630e9a004]
[fv-az95-172:69187] [ 9] plumed(+0xf698)[0x563630e95698]
[fv-az95-172:69187] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fee3f97c0b3]
[fv-az95-172:69187] [11] plumed(+0xf76e)[0x563630e9576e]
[fv-az95-172:69187] *** End of error message ***
</pre>
{% endraw %}
