**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w44-s8.498/plumed.dat   
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
[fv-az95-172:42545] *** Process received signal ***
[fv-az95-172:42545] Signal: Aborted (6)
[fv-az95-172:42545] Signal code:  (-6)
[fv-az95-172:42545] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc8ec9e0210]
[fv-az95-172:42545] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc8ec9e018b]
[fv-az95-172:42545] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc8ec9bf859]
[fv-az95-172:42545] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc8ecc47911]
[fv-az95-172:42545] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc8ecc5338c]
[fv-az95-172:42545] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc8ecc533f7]
[fv-az95-172:42545] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc8ecc536a9]
[fv-az95-172:42545] [ 7] plumed(+0xf47d)[0x558f975b347d]
[fv-az95-172:42545] [ 8] plumed(+0x14004)[0x558f975b8004]
[fv-az95-172:42545] [ 9] plumed(+0xf698)[0x558f975b3698]
[fv-az95-172:42545] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc8ec9c10b3]
[fv-az95-172:42545] [11] plumed(+0xf76e)[0x558f975b376e]
[fv-az95-172:42545] *** End of error message ***
</pre>
{% endraw %}
