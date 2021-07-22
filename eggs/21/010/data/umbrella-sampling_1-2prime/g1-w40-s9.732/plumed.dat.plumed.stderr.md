**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w40-s9.732/plumed.dat   
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
[fv-az95-172:38221] *** Process received signal ***
[fv-az95-172:38221] Signal: Aborted (6)
[fv-az95-172:38221] Signal code:  (-6)
[fv-az95-172:38221] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa232e2a210]
[fv-az95-172:38221] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa232e2a18b]
[fv-az95-172:38221] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa232e09859]
[fv-az95-172:38221] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa233091911]
[fv-az95-172:38221] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa23309d38c]
[fv-az95-172:38221] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa23309d3f7]
[fv-az95-172:38221] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa23309d6a9]
[fv-az95-172:38221] [ 7] plumed(+0xf47d)[0x55ea7506447d]
[fv-az95-172:38221] [ 8] plumed(+0x14004)[0x55ea75069004]
[fv-az95-172:38221] [ 9] plumed(+0xf698)[0x55ea75064698]
[fv-az95-172:38221] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa232e0b0b3]
[fv-az95-172:38221] [11] plumed(+0xf76e)[0x55ea7506476e]
[fv-az95-172:38221] *** End of error message ***
</pre>
{% endraw %}
