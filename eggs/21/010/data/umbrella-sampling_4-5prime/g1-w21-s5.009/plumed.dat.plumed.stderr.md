**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w21-s5.009/plumed.dat   
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
[fv-az95-172:41932] *** Process received signal ***
[fv-az95-172:41932] Signal: Aborted (6)
[fv-az95-172:41932] Signal code:  (-6)
[fv-az95-172:41932] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2646df2210]
[fv-az95-172:41932] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2646df218b]
[fv-az95-172:41932] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2646dd1859]
[fv-az95-172:41932] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2647059911]
[fv-az95-172:41932] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f264706538c]
[fv-az95-172:41932] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f26470653f7]
[fv-az95-172:41932] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f26470656a9]
[fv-az95-172:41932] [ 7] plumed(+0xf47d)[0x562a13f1547d]
[fv-az95-172:41932] [ 8] plumed(+0x14004)[0x562a13f1a004]
[fv-az95-172:41932] [ 9] plumed(+0xf698)[0x562a13f15698]
[fv-az95-172:41932] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2646dd30b3]
[fv-az95-172:41932] [11] plumed(+0xf76e)[0x562a13f1576e]
[fv-az95-172:41932] *** End of error message ***
</pre>
{% endraw %}
