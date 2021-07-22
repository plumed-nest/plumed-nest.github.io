**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w24-s9.050/plumed.dat   
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
[fv-az95-172:44834] *** Process received signal ***
[fv-az95-172:44834] Signal: Aborted (6)
[fv-az95-172:44834] Signal code:  (-6)
[fv-az95-172:44834] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f893da31210]
[fv-az95-172:44834] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f893da3118b]
[fv-az95-172:44834] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f893da10859]
[fv-az95-172:44834] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f893dc98911]
[fv-az95-172:44834] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f893dca438c]
[fv-az95-172:44834] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f893dca43f7]
[fv-az95-172:44834] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f893dca46a9]
[fv-az95-172:44834] [ 7] plumed(+0xf47d)[0x55e941ccb47d]
[fv-az95-172:44834] [ 8] plumed(+0x14004)[0x55e941cd0004]
[fv-az95-172:44834] [ 9] plumed(+0xf698)[0x55e941ccb698]
[fv-az95-172:44834] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f893da120b3]
[fv-az95-172:44834] [11] plumed(+0xf76e)[0x55e941ccb76e]
[fv-az95-172:44834] *** End of error message ***
</pre>
{% endraw %}
