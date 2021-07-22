**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w12-s5.736/plumed.dat   
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
[fv-az95-172:40753] *** Process received signal ***
[fv-az95-172:40753] Signal: Aborted (6)
[fv-az95-172:40753] Signal code:  (-6)
[fv-az95-172:40753] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f34c796f210]
[fv-az95-172:40753] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f34c796f18b]
[fv-az95-172:40753] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f34c794e859]
[fv-az95-172:40753] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f34c7bd6911]
[fv-az95-172:40753] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f34c7be238c]
[fv-az95-172:40753] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f34c7be23f7]
[fv-az95-172:40753] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f34c7be26a9]
[fv-az95-172:40753] [ 7] plumed(+0xf47d)[0x559d3824147d]
[fv-az95-172:40753] [ 8] plumed(+0x14004)[0x559d38246004]
[fv-az95-172:40753] [ 9] plumed(+0xf698)[0x559d38241698]
[fv-az95-172:40753] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f34c79500b3]
[fv-az95-172:40753] [11] plumed(+0xf76e)[0x559d3824176e]
[fv-az95-172:40753] *** End of error message ***
</pre>
{% endraw %}
