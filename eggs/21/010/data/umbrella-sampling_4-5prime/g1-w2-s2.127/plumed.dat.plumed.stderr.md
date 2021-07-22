**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w2-s2.127/plumed.dat   
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
[fv-az95-172:41879] *** Process received signal ***
[fv-az95-172:41879] Signal: Aborted (6)
[fv-az95-172:41879] Signal code:  (-6)
[fv-az95-172:41879] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0383b06210]
[fv-az95-172:41879] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0383b0618b]
[fv-az95-172:41879] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0383ae5859]
[fv-az95-172:41879] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0383d6d911]
[fv-az95-172:41879] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0383d7938c]
[fv-az95-172:41879] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0383d793f7]
[fv-az95-172:41879] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0383d796a9]
[fv-az95-172:41879] [ 7] plumed(+0xf47d)[0x55a4e415d47d]
[fv-az95-172:41879] [ 8] plumed(+0x14004)[0x55a4e4162004]
[fv-az95-172:41879] [ 9] plumed(+0xf698)[0x55a4e415d698]
[fv-az95-172:41879] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0383ae70b3]
[fv-az95-172:41879] [11] plumed(+0xf76e)[0x55a4e415d76e]
[fv-az95-172:41879] *** End of error message ***
</pre>
{% endraw %}
