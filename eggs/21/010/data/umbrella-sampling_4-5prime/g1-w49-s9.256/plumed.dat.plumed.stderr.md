**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w49-s9.256/plumed.dat   
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
[fv-az95-172:42667] *** Process received signal ***
[fv-az95-172:42667] Signal: Aborted (6)
[fv-az95-172:42667] Signal code:  (-6)
[fv-az95-172:42667] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff3e9278210]
[fv-az95-172:42667] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff3e927818b]
[fv-az95-172:42667] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff3e9257859]
[fv-az95-172:42667] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff3e94df911]
[fv-az95-172:42667] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff3e94eb38c]
[fv-az95-172:42667] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff3e94eb3f7]
[fv-az95-172:42667] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ff3e94eb6a9]
[fv-az95-172:42667] [ 7] plumed(+0xf47d)[0x562a6ec1447d]
[fv-az95-172:42667] [ 8] plumed(+0x14004)[0x562a6ec19004]
[fv-az95-172:42667] [ 9] plumed(+0xf698)[0x562a6ec14698]
[fv-az95-172:42667] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff3e92590b3]
[fv-az95-172:42667] [11] plumed(+0xf76e)[0x562a6ec1476e]
[fv-az95-172:42667] *** End of error message ***
</pre>
{% endraw %}
