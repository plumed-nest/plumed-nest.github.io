**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w12-s5.450/plumed.dat   
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
[fv-az95-172:44513] *** Process received signal ***
[fv-az95-172:44513] Signal: Aborted (6)
[fv-az95-172:44513] Signal code:  (-6)
[fv-az95-172:44513] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fcf03983210]
[fv-az95-172:44513] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fcf0398318b]
[fv-az95-172:44513] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fcf03962859]
[fv-az95-172:44513] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fcf03bea911]
[fv-az95-172:44513] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fcf03bf638c]
[fv-az95-172:44513] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fcf03bf63f7]
[fv-az95-172:44513] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fcf03bf66a9]
[fv-az95-172:44513] [ 7] plumed(+0xf47d)[0x55b03850547d]
[fv-az95-172:44513] [ 8] plumed(+0x14004)[0x55b03850a004]
[fv-az95-172:44513] [ 9] plumed(+0xf698)[0x55b038505698]
[fv-az95-172:44513] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fcf039640b3]
[fv-az95-172:44513] [11] plumed(+0xf76e)[0x55b03850576e]
[fv-az95-172:44513] *** End of error message ***
</pre>
{% endraw %}
