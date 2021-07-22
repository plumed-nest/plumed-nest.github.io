**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g8-w1-s5.6855/plumed.dat   
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
[fv-az95-172:41583] *** Process received signal ***
[fv-az95-172:41583] Signal: Aborted (6)
[fv-az95-172:41583] Signal code:  (-6)
[fv-az95-172:41583] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff7d50c5210]
[fv-az95-172:41583] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff7d50c518b]
[fv-az95-172:41583] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff7d50a4859]
[fv-az95-172:41583] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff7d532c911]
[fv-az95-172:41583] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff7d533838c]
[fv-az95-172:41583] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff7d53383f7]
[fv-az95-172:41583] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ff7d53386a9]
[fv-az95-172:41583] [ 7] plumed(+0xf47d)[0x555721c7647d]
[fv-az95-172:41583] [ 8] plumed(+0x14004)[0x555721c7b004]
[fv-az95-172:41583] [ 9] plumed(+0xf698)[0x555721c76698]
[fv-az95-172:41583] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff7d50a60b3]
[fv-az95-172:41583] [11] plumed(+0xf76e)[0x555721c7676e]
[fv-az95-172:41583] *** End of error message ***
</pre>
{% endraw %}
