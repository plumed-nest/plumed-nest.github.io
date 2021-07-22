**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w3-s3.399/plumed.dat   
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
[fv-az95-172:41145] *** Process received signal ***
[fv-az95-172:41145] Signal: Aborted (6)
[fv-az95-172:41145] Signal code:  (-6)
[fv-az95-172:41145] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f1d0a0d9210]
[fv-az95-172:41145] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f1d0a0d918b]
[fv-az95-172:41145] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f1d0a0b8859]
[fv-az95-172:41145] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f1d0a340911]
[fv-az95-172:41145] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f1d0a34c38c]
[fv-az95-172:41145] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f1d0a34c3f7]
[fv-az95-172:41145] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f1d0a34c6a9]
[fv-az95-172:41145] [ 7] plumed(+0xf47d)[0x563f0833047d]
[fv-az95-172:41145] [ 8] plumed(+0x14004)[0x563f08335004]
[fv-az95-172:41145] [ 9] plumed(+0xf698)[0x563f08330698]
[fv-az95-172:41145] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f1d0a0ba0b3]
[fv-az95-172:41145] [11] plumed(+0xf76e)[0x563f0833076e]
[fv-az95-172:41145] *** End of error message ***
</pre>
{% endraw %}
