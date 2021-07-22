**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w11-s5.476/plumed.dat   
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
[fv-az95-172:40728] *** Process received signal ***
[fv-az95-172:40728] Signal: Aborted (6)
[fv-az95-172:40728] Signal code:  (-6)
[fv-az95-172:40728] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3d9a044210]
[fv-az95-172:40728] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3d9a04418b]
[fv-az95-172:40728] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3d9a023859]
[fv-az95-172:40728] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3d9a2ab911]
[fv-az95-172:40728] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f3d9a2b738c]
[fv-az95-172:40728] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f3d9a2b73f7]
[fv-az95-172:40728] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f3d9a2b76a9]
[fv-az95-172:40728] [ 7] plumed(+0xf47d)[0x55e10062647d]
[fv-az95-172:40728] [ 8] plumed(+0x14004)[0x55e10062b004]
[fv-az95-172:40728] [ 9] plumed(+0xf698)[0x55e100626698]
[fv-az95-172:40728] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3d9a0250b3]
[fv-az95-172:40728] [11] plumed(+0xf76e)[0x55e10062676e]
[fv-az95-172:40728] *** End of error message ***
</pre>
{% endraw %}
