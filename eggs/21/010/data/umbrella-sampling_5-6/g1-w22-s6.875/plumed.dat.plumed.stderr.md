**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w22-s6.875/plumed.dat   
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
[fv-az95-172:43553] *** Process received signal ***
[fv-az95-172:43553] Signal: Aborted (6)
[fv-az95-172:43553] Signal code:  (-6)
[fv-az95-172:43553] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f7c81f9a210]
[fv-az95-172:43553] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f7c81f9a18b]
[fv-az95-172:43553] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7c81f79859]
[fv-az95-172:43553] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f7c82201911]
[fv-az95-172:43553] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f7c8220d38c]
[fv-az95-172:43553] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f7c8220d3f7]
[fv-az95-172:43553] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f7c8220d6a9]
[fv-az95-172:43553] [ 7] plumed(+0xf47d)[0x561c298cb47d]
[fv-az95-172:43553] [ 8] plumed(+0x14004)[0x561c298d0004]
[fv-az95-172:43553] [ 9] plumed(+0xf698)[0x561c298cb698]
[fv-az95-172:43553] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f7c81f7b0b3]
[fv-az95-172:43553] [11] plumed(+0xf76e)[0x561c298cb76e]
[fv-az95-172:43553] *** End of error message ***
</pre>
{% endraw %}
