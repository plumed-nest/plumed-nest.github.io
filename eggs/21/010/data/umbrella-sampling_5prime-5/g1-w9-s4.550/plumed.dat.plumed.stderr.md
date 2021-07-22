**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w9-s4.550/plumed.dat   
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
[fv-az95-172:45155] *** Process received signal ***
[fv-az95-172:45155] Signal: Aborted (6)
[fv-az95-172:45155] Signal code:  (-6)
[fv-az95-172:45155] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fbbd441f210]
[fv-az95-172:45155] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fbbd441f18b]
[fv-az95-172:45155] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fbbd43fe859]
[fv-az95-172:45155] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fbbd4686911]
[fv-az95-172:45155] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fbbd469238c]
[fv-az95-172:45155] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fbbd46923f7]
[fv-az95-172:45155] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fbbd46926a9]
[fv-az95-172:45155] [ 7] plumed(+0xf47d)[0x56042dc1d47d]
[fv-az95-172:45155] [ 8] plumed(+0x14004)[0x56042dc22004]
[fv-az95-172:45155] [ 9] plumed(+0xf698)[0x56042dc1d698]
[fv-az95-172:45155] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fbbd44000b3]
[fv-az95-172:45155] [11] plumed(+0xf76e)[0x56042dc1d76e]
[fv-az95-172:45155] *** End of error message ***
</pre>
{% endraw %}
