**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g202-w1-s4.503/plumed.dat   
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
[fv-az95-172:41365] *** Process received signal ***
[fv-az95-172:41365] Signal: Aborted (6)
[fv-az95-172:41365] Signal code:  (-6)
[fv-az95-172:41365] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f10558d3210]
[fv-az95-172:41365] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f10558d318b]
[fv-az95-172:41365] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f10558b2859]
[fv-az95-172:41365] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f1055b3a911]
[fv-az95-172:41365] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f1055b4638c]
[fv-az95-172:41365] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f1055b463f7]
[fv-az95-172:41365] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f1055b466a9]
[fv-az95-172:41365] [ 7] plumed(+0xf47d)[0x562642c0d47d]
[fv-az95-172:41365] [ 8] plumed(+0x14004)[0x562642c12004]
[fv-az95-172:41365] [ 9] plumed(+0xf698)[0x562642c0d698]
[fv-az95-172:41365] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f10558b40b3]
[fv-az95-172:41365] [11] plumed(+0xf76e)[0x562642c0d76e]
[fv-az95-172:41365] *** End of error message ***
</pre>
{% endraw %}
