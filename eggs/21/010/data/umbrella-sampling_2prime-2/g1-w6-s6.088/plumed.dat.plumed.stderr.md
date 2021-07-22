**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w6-s6.088/plumed.dat   
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
[fv-az95-172:40140] *** Process received signal ***
[fv-az95-172:40140] Signal: Aborted (6)
[fv-az95-172:40140] Signal code:  (-6)
[fv-az95-172:40140] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3ff53f8210]
[fv-az95-172:40140] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3ff53f818b]
[fv-az95-172:40140] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3ff53d7859]
[fv-az95-172:40140] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3ff565f911]
[fv-az95-172:40140] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f3ff566b38c]
[fv-az95-172:40140] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f3ff566b3f7]
[fv-az95-172:40140] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f3ff566b6a9]
[fv-az95-172:40140] [ 7] plumed(+0xf47d)[0x55bc5da2f47d]
[fv-az95-172:40140] [ 8] plumed(+0x14004)[0x55bc5da34004]
[fv-az95-172:40140] [ 9] plumed(+0xf698)[0x55bc5da2f698]
[fv-az95-172:40140] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3ff53d90b3]
[fv-az95-172:40140] [11] plumed(+0xf76e)[0x55bc5da2f76e]
[fv-az95-172:40140] *** End of error message ***
</pre>
{% endraw %}
