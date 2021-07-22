**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w37-s9.084/plumed.dat   
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
[fv-az95-172:38124] *** Process received signal ***
[fv-az95-172:38124] Signal: Aborted (6)
[fv-az95-172:38124] Signal code:  (-6)
[fv-az95-172:38124] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff937a8f210]
[fv-az95-172:38124] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff937a8f18b]
[fv-az95-172:38124] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff937a6e859]
[fv-az95-172:38124] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff937cf6911]
[fv-az95-172:38124] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff937d0238c]
[fv-az95-172:38124] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff937d023f7]
[fv-az95-172:38124] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ff937d026a9]
[fv-az95-172:38124] [ 7] plumed(+0xf47d)[0x55786ae5047d]
[fv-az95-172:38124] [ 8] plumed(+0x14004)[0x55786ae55004]
[fv-az95-172:38124] [ 9] plumed(+0xf698)[0x55786ae50698]
[fv-az95-172:38124] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff937a700b3]
[fv-az95-172:38124] [11] plumed(+0xf76e)[0x55786ae5076e]
[fv-az95-172:38124] *** End of error message ***
</pre>
{% endraw %}
