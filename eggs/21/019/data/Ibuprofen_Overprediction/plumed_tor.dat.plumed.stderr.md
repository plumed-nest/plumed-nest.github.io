**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
(download [zipped raw stdout](plumed_tor.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATOMS141=9314,9319,9310,9313
Maybe a missing space or a typo?
[fv-az95-172:34778] *** Process received signal ***
[fv-az95-172:34778] Signal: Aborted (6)
[fv-az95-172:34778] Signal code:  (-6)
[fv-az95-172:34778] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f70f2098210]
[fv-az95-172:34778] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f70f209818b]
[fv-az95-172:34778] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f70f2077859]
[fv-az95-172:34778] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f70f22ff911]
[fv-az95-172:34778] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f70f230b38c]
[fv-az95-172:34778] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f70f230b3f7]
[fv-az95-172:34778] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f70f230b6a9]
[fv-az95-172:34778] [ 7] plumed(+0xf47d)[0x56197c89647d]
[fv-az95-172:34778] [ 8] plumed(+0x14004)[0x56197c89b004]
[fv-az95-172:34778] [ 9] plumed(+0xf698)[0x56197c896698]
[fv-az95-172:34778] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f70f20790b3]
[fv-az95-172:34778] [11] plumed(+0xf76e)[0x56197c89676e]
[fv-az95-172:34778] *** End of error message ***
</pre>
{% endraw %}
