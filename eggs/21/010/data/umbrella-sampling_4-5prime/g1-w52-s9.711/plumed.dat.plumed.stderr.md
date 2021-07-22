**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w52-s9.711/plumed.dat   
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
[fv-az95-172:42766] *** Process received signal ***
[fv-az95-172:42766] Signal: Aborted (6)
[fv-az95-172:42766] Signal code:  (-6)
[fv-az95-172:42766] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f8319e61210]
[fv-az95-172:42766] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f8319e6118b]
[fv-az95-172:42766] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f8319e40859]
[fv-az95-172:42766] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f831a0c8911]
[fv-az95-172:42766] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f831a0d438c]
[fv-az95-172:42766] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f831a0d43f7]
[fv-az95-172:42766] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f831a0d46a9]
[fv-az95-172:42766] [ 7] plumed(+0xf47d)[0x5573bb2f547d]
[fv-az95-172:42766] [ 8] plumed(+0x14004)[0x5573bb2fa004]
[fv-az95-172:42766] [ 9] plumed(+0xf698)[0x5573bb2f5698]
[fv-az95-172:42766] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f8319e420b3]
[fv-az95-172:42766] [11] plumed(+0xf76e)[0x5573bb2f576e]
[fv-az95-172:42766] *** End of error message ***
</pre>
{% endraw %}
