**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w13-s5.995/plumed.dat   
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
[fv-az95-172:40777] *** Process received signal ***
[fv-az95-172:40777] Signal: Aborted (6)
[fv-az95-172:40777] Signal code:  (-6)
[fv-az95-172:40777] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb0b5433210]
[fv-az95-172:40777] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb0b543318b]
[fv-az95-172:40777] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb0b5412859]
[fv-az95-172:40777] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb0b569a911]
[fv-az95-172:40777] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb0b56a638c]
[fv-az95-172:40777] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb0b56a63f7]
[fv-az95-172:40777] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fb0b56a66a9]
[fv-az95-172:40777] [ 7] plumed(+0xf47d)[0x5613ba84247d]
[fv-az95-172:40777] [ 8] plumed(+0x14004)[0x5613ba847004]
[fv-az95-172:40777] [ 9] plumed(+0xf698)[0x5613ba842698]
[fv-az95-172:40777] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb0b54140b3]
[fv-az95-172:40777] [11] plumed(+0xf76e)[0x5613ba84276e]
[fv-az95-172:40777] *** End of error message ***
</pre>
{% endraw %}
