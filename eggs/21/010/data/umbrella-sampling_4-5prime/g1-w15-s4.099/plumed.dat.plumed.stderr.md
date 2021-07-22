**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w15-s4.099/plumed.dat   
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
[fv-az95-172:41756] *** Process received signal ***
[fv-az95-172:41756] Signal: Aborted (6)
[fv-az95-172:41756] Signal code:  (-6)
[fv-az95-172:41756] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff93d77f210]
[fv-az95-172:41756] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff93d77f18b]
[fv-az95-172:41756] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff93d75e859]
[fv-az95-172:41756] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff93d9e6911]
[fv-az95-172:41756] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff93d9f238c]
[fv-az95-172:41756] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff93d9f23f7]
[fv-az95-172:41756] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ff93d9f26a9]
[fv-az95-172:41756] [ 7] plumed(+0xf47d)[0x5634f37d147d]
[fv-az95-172:41756] [ 8] plumed(+0x14004)[0x5634f37d6004]
[fv-az95-172:41756] [ 9] plumed(+0xf698)[0x5634f37d1698]
[fv-az95-172:41756] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff93d7600b3]
[fv-az95-172:41756] [11] plumed(+0xf76e)[0x5634f37d176e]
[fv-az95-172:41756] *** End of error message ***
</pre>
{% endraw %}
