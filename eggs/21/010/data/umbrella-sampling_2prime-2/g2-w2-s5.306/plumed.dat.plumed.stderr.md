**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g2-w2-s5.306/plumed.dat   
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
[fv-az95-172:40288] *** Process received signal ***
[fv-az95-172:40288] Signal: Aborted (6)
[fv-az95-172:40288] Signal code:  (-6)
[fv-az95-172:40288] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f9c9fe56210]
[fv-az95-172:40288] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f9c9fe5618b]
[fv-az95-172:40288] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f9c9fe35859]
[fv-az95-172:40288] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f9ca00bd911]
[fv-az95-172:40288] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f9ca00c938c]
[fv-az95-172:40288] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f9ca00c93f7]
[fv-az95-172:40288] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f9ca00c96a9]
[fv-az95-172:40288] [ 7] plumed(+0xf47d)[0x5585c062047d]
[fv-az95-172:40288] [ 8] plumed(+0x14004)[0x5585c0625004]
[fv-az95-172:40288] [ 9] plumed(+0xf698)[0x5585c0620698]
[fv-az95-172:40288] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f9c9fe370b3]
[fv-az95-172:40288] [11] plumed(+0xf76e)[0x5585c062076e]
[fv-az95-172:40288] *** End of error message ***
</pre>
{% endraw %}
