**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w32-s9.375/plumed.dat   
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
[fv-az95-172:43821] *** Process received signal ***
[fv-az95-172:43821] Signal: Aborted (6)
[fv-az95-172:43821] Signal code:  (-6)
[fv-az95-172:43821] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f7876734210]
[fv-az95-172:43821] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f787673418b]
[fv-az95-172:43821] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7876713859]
[fv-az95-172:43821] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f787699b911]
[fv-az95-172:43821] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f78769a738c]
[fv-az95-172:43821] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f78769a73f7]
[fv-az95-172:43821] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f78769a76a9]
[fv-az95-172:43821] [ 7] plumed(+0xf47d)[0x56379121947d]
[fv-az95-172:43821] [ 8] plumed(+0x14004)[0x56379121e004]
[fv-az95-172:43821] [ 9] plumed(+0xf698)[0x563791219698]
[fv-az95-172:43821] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f78767150b3]
[fv-az95-172:43821] [11] plumed(+0xf76e)[0x56379121976e]
[fv-az95-172:43821] *** End of error message ***
</pre>
{% endraw %}
