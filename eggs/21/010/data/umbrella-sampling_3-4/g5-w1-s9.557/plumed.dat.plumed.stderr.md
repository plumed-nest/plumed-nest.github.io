**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g5-w1-s9.557/plumed.dat   
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
[fv-az95-172:41461] *** Process received signal ***
[fv-az95-172:41461] Signal: Aborted (6)
[fv-az95-172:41461] Signal code:  (-6)
[fv-az95-172:41461] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fda4f837210]
[fv-az95-172:41461] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fda4f83718b]
[fv-az95-172:41461] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fda4f816859]
[fv-az95-172:41461] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fda4fa9e911]
[fv-az95-172:41461] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fda4faaa38c]
[fv-az95-172:41461] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fda4faaa3f7]
[fv-az95-172:41461] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fda4faaa6a9]
[fv-az95-172:41461] [ 7] plumed(+0xf47d)[0x555e3b45547d]
[fv-az95-172:41461] [ 8] plumed(+0x14004)[0x555e3b45a004]
[fv-az95-172:41461] [ 9] plumed(+0xf698)[0x555e3b455698]
[fv-az95-172:41461] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fda4f8180b3]
[fv-az95-172:41461] [11] plumed(+0xf76e)[0x555e3b45576e]
[fv-az95-172:41461] *** End of error message ***
</pre>
{% endraw %}
