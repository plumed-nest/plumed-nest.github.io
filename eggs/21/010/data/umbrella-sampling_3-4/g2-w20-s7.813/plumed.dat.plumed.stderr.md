**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w20-s7.813/plumed.dat   
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
[fv-az95-172:40973] *** Process received signal ***
[fv-az95-172:40973] Signal: Aborted (6)
[fv-az95-172:40973] Signal code:  (-6)
[fv-az95-172:40973] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f1e77c37210]
[fv-az95-172:40973] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f1e77c3718b]
[fv-az95-172:40973] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f1e77c16859]
[fv-az95-172:40973] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f1e77e9e911]
[fv-az95-172:40973] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f1e77eaa38c]
[fv-az95-172:40973] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f1e77eaa3f7]
[fv-az95-172:40973] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f1e77eaa6a9]
[fv-az95-172:40973] [ 7] plumed(+0xf47d)[0x55e307c8e47d]
[fv-az95-172:40973] [ 8] plumed(+0x14004)[0x55e307c93004]
[fv-az95-172:40973] [ 9] plumed(+0xf698)[0x55e307c8e698]
[fv-az95-172:40973] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f1e77c180b3]
[fv-az95-172:40973] [11] plumed(+0xf76e)[0x55e307c8e76e]
[fv-az95-172:40973] *** End of error message ***
</pre>
{% endraw %}
