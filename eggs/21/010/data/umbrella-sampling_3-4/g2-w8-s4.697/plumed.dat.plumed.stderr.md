**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w8-s4.697/plumed.dat   
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
[fv-az95-172:41267] *** Process received signal ***
[fv-az95-172:41267] Signal: Aborted (6)
[fv-az95-172:41267] Signal code:  (-6)
[fv-az95-172:41267] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f26ec89e210]
[fv-az95-172:41267] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f26ec89e18b]
[fv-az95-172:41267] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f26ec87d859]
[fv-az95-172:41267] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f26ecb05911]
[fv-az95-172:41267] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f26ecb1138c]
[fv-az95-172:41267] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f26ecb113f7]
[fv-az95-172:41267] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f26ecb116a9]
[fv-az95-172:41267] [ 7] plumed(+0xf47d)[0x555fa64ea47d]
[fv-az95-172:41267] [ 8] plumed(+0x14004)[0x555fa64ef004]
[fv-az95-172:41267] [ 9] plumed(+0xf698)[0x555fa64ea698]
[fv-az95-172:41267] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f26ec87f0b3]
[fv-az95-172:41267] [11] plumed(+0xf76e)[0x555fa64ea76e]
[fv-az95-172:41267] *** End of error message ***
</pre>
{% endraw %}
