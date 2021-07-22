**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w3-s5.758/plumed.dat   
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
[fv-az95-172:39305] *** Process received signal ***
[fv-az95-172:39305] Signal: Aborted (6)
[fv-az95-172:39305] Signal code:  (-6)
[fv-az95-172:39305] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa321cd5210]
[fv-az95-172:39305] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa321cd518b]
[fv-az95-172:39305] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa321cb4859]
[fv-az95-172:39305] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa321f3c911]
[fv-az95-172:39305] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa321f4838c]
[fv-az95-172:39305] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa321f483f7]
[fv-az95-172:39305] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa321f486a9]
[fv-az95-172:39305] [ 7] plumed(+0xf47d)[0x560d1ad5b47d]
[fv-az95-172:39305] [ 8] plumed(+0x14004)[0x560d1ad60004]
[fv-az95-172:39305] [ 9] plumed(+0xf698)[0x560d1ad5b698]
[fv-az95-172:39305] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa321cb60b3]
[fv-az95-172:39305] [11] plumed(+0xf76e)[0x560d1ad5b76e]
[fv-az95-172:39305] *** End of error message ***
</pre>
{% endraw %}
