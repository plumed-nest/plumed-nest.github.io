**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w58-s10.621/plumed.dat   
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
[fv-az95-172:42912] *** Process received signal ***
[fv-az95-172:42912] Signal: Aborted (6)
[fv-az95-172:42912] Signal code:  (-6)
[fv-az95-172:42912] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa3a440e210]
[fv-az95-172:42912] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa3a440e18b]
[fv-az95-172:42912] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa3a43ed859]
[fv-az95-172:42912] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa3a4675911]
[fv-az95-172:42912] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa3a468138c]
[fv-az95-172:42912] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa3a46813f7]
[fv-az95-172:42912] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa3a46816a9]
[fv-az95-172:42912] [ 7] plumed(+0xf47d)[0x56367ae4c47d]
[fv-az95-172:42912] [ 8] plumed(+0x14004)[0x56367ae51004]
[fv-az95-172:42912] [ 9] plumed(+0xf698)[0x56367ae4c698]
[fv-az95-172:42912] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa3a43ef0b3]
[fv-az95-172:42912] [11] plumed(+0xf76e)[0x56367ae4c76e]
[fv-az95-172:42912] *** End of error message ***
</pre>
{% endraw %}
