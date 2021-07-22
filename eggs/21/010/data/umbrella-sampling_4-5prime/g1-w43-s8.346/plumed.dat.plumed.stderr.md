**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w43-s8.346/plumed.dat   
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
[fv-az95-172:42521] *** Process received signal ***
[fv-az95-172:42521] Signal: Aborted (6)
[fv-az95-172:42521] Signal code:  (-6)
[fv-az95-172:42521] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5008089210]
[fv-az95-172:42521] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f500808918b]
[fv-az95-172:42521] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5008068859]
[fv-az95-172:42521] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f50082f0911]
[fv-az95-172:42521] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f50082fc38c]
[fv-az95-172:42521] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f50082fc3f7]
[fv-az95-172:42521] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f50082fc6a9]
[fv-az95-172:42521] [ 7] plumed(+0xf47d)[0x5570d4e3247d]
[fv-az95-172:42521] [ 8] plumed(+0x14004)[0x5570d4e37004]
[fv-az95-172:42521] [ 9] plumed(+0xf698)[0x5570d4e32698]
[fv-az95-172:42521] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f500806a0b3]
[fv-az95-172:42521] [11] plumed(+0xf76e)[0x5570d4e3276e]
[fv-az95-172:42521] *** End of error message ***
</pre>
{% endraw %}
