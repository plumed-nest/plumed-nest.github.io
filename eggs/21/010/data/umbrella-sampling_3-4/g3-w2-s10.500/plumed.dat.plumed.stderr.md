**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g3-w2-s10.500/plumed.dat   
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
[fv-az95-172:41437] *** Process received signal ***
[fv-az95-172:41437] Signal: Aborted (6)
[fv-az95-172:41437] Signal code:  (-6)
[fv-az95-172:41437] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f7c40abe210]
[fv-az95-172:41437] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f7c40abe18b]
[fv-az95-172:41437] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7c40a9d859]
[fv-az95-172:41437] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f7c40d25911]
[fv-az95-172:41437] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f7c40d3138c]
[fv-az95-172:41437] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f7c40d313f7]
[fv-az95-172:41437] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f7c40d316a9]
[fv-az95-172:41437] [ 7] plumed(+0xf47d)[0x555d2b97647d]
[fv-az95-172:41437] [ 8] plumed(+0x14004)[0x555d2b97b004]
[fv-az95-172:41437] [ 9] plumed(+0xf698)[0x555d2b976698]
[fv-az95-172:41437] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f7c40a9f0b3]
[fv-az95-172:41437] [11] plumed(+0xf76e)[0x555d2b97676e]
[fv-az95-172:41437] *** End of error message ***
</pre>
{% endraw %}
