**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w34-s8.436/plumed.dat   
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
[fv-az95-172:38051] *** Process received signal ***
[fv-az95-172:38051] Signal: Aborted (6)
[fv-az95-172:38051] Signal code:  (-6)
[fv-az95-172:38051] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4217ba9210]
[fv-az95-172:38051] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f4217ba918b]
[fv-az95-172:38051] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4217b88859]
[fv-az95-172:38051] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4217e10911]
[fv-az95-172:38051] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f4217e1c38c]
[fv-az95-172:38051] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f4217e1c3f7]
[fv-az95-172:38051] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f4217e1c6a9]
[fv-az95-172:38051] [ 7] plumed(+0xf47d)[0x5589b6e2b47d]
[fv-az95-172:38051] [ 8] plumed(+0x14004)[0x5589b6e30004]
[fv-az95-172:38051] [ 9] plumed(+0xf698)[0x5589b6e2b698]
[fv-az95-172:38051] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f4217b8a0b3]
[fv-az95-172:38051] [11] plumed(+0xf76e)[0x5589b6e2b76e]
[fv-az95-172:38051] *** End of error message ***
</pre>
{% endraw %}
