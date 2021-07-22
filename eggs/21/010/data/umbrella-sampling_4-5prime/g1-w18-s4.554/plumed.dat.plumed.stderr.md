**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w18-s4.554/plumed.dat   
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
[fv-az95-172:41829] *** Process received signal ***
[fv-az95-172:41829] Signal: Aborted (6)
[fv-az95-172:41829] Signal code:  (-6)
[fv-az95-172:41829] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe98693b210]
[fv-az95-172:41829] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe98693b18b]
[fv-az95-172:41829] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe98691a859]
[fv-az95-172:41829] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe986ba2911]
[fv-az95-172:41829] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe986bae38c]
[fv-az95-172:41829] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe986bae3f7]
[fv-az95-172:41829] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fe986bae6a9]
[fv-az95-172:41829] [ 7] plumed(+0xf47d)[0x559d347af47d]
[fv-az95-172:41829] [ 8] plumed(+0x14004)[0x559d347b4004]
[fv-az95-172:41829] [ 9] plumed(+0xf698)[0x559d347af698]
[fv-az95-172:41829] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe98691c0b3]
[fv-az95-172:41829] [11] plumed(+0xf76e)[0x559d347af76e]
[fv-az95-172:41829] *** End of error message ***
</pre>
{% endraw %}
