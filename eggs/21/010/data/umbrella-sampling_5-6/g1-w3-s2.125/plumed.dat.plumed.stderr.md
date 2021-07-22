**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w3-s2.125/plumed.dat   
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
[fv-az95-172:43748] *** Process received signal ***
[fv-az95-172:43748] Signal: Aborted (6)
[fv-az95-172:43748] Signal code:  (-6)
[fv-az95-172:43748] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f14a7739210]
[fv-az95-172:43748] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f14a773918b]
[fv-az95-172:43748] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f14a7718859]
[fv-az95-172:43748] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f14a79a0911]
[fv-az95-172:43748] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f14a79ac38c]
[fv-az95-172:43748] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f14a79ac3f7]
[fv-az95-172:43748] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f14a79ac6a9]
[fv-az95-172:43748] [ 7] plumed(+0xf47d)[0x55a0e890547d]
[fv-az95-172:43748] [ 8] plumed(+0x14004)[0x55a0e890a004]
[fv-az95-172:43748] [ 9] plumed(+0xf698)[0x55a0e8905698]
[fv-az95-172:43748] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f14a771a0b3]
[fv-az95-172:43748] [11] plumed(+0xf76e)[0x55a0e890576e]
[fv-az95-172:43748] *** End of error message ***
</pre>
{% endraw %}
