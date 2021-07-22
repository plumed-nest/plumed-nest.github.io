**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w6-s6.308/plumed.dat   
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
[fv-az95-172:39378] *** Process received signal ***
[fv-az95-172:39378] Signal: Aborted (6)
[fv-az95-172:39378] Signal code:  (-6)
[fv-az95-172:39378] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2fd515c210]
[fv-az95-172:39378] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2fd515c18b]
[fv-az95-172:39378] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2fd513b859]
[fv-az95-172:39378] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2fd53c3911]
[fv-az95-172:39378] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2fd53cf38c]
[fv-az95-172:39378] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2fd53cf3f7]
[fv-az95-172:39378] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f2fd53cf6a9]
[fv-az95-172:39378] [ 7] plumed(+0xf47d)[0x56408316247d]
[fv-az95-172:39378] [ 8] plumed(+0x14004)[0x564083167004]
[fv-az95-172:39378] [ 9] plumed(+0xf698)[0x564083162698]
[fv-az95-172:39378] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2fd513d0b3]
[fv-az95-172:39378] [11] plumed(+0xf76e)[0x56408316276e]
[fv-az95-172:39378] *** End of error message ***
</pre>
{% endraw %}
