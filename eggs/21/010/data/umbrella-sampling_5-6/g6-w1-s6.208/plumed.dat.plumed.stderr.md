**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g6-w1-s6.208/plumed.dat   
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
[fv-az95-172:44363] *** Process received signal ***
[fv-az95-172:44363] Signal: Aborted (6)
[fv-az95-172:44363] Signal code:  (-6)
[fv-az95-172:44363] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe73e8ee210]
[fv-az95-172:44363] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe73e8ee18b]
[fv-az95-172:44363] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe73e8cd859]
[fv-az95-172:44363] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe73eb55911]
[fv-az95-172:44363] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe73eb6138c]
[fv-az95-172:44363] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe73eb613f7]
[fv-az95-172:44363] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fe73eb616a9]
[fv-az95-172:44363] [ 7] plumed(+0xf47d)[0x5638d51a147d]
[fv-az95-172:44363] [ 8] plumed(+0x14004)[0x5638d51a6004]
[fv-az95-172:44363] [ 9] plumed(+0xf698)[0x5638d51a1698]
[fv-az95-172:44363] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe73e8cf0b3]
[fv-az95-172:44363] [11] plumed(+0xf76e)[0x5638d51a176e]
[fv-az95-172:44363] *** End of error message ***
</pre>
{% endraw %}
