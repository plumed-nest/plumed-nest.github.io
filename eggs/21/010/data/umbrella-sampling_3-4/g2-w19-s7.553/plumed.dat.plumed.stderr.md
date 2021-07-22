**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w19-s7.553/plumed.dat   
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
[fv-az95-172:40924] *** Process received signal ***
[fv-az95-172:40924] Signal: Aborted (6)
[fv-az95-172:40924] Signal code:  (-6)
[fv-az95-172:40924] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7efc73eae210]
[fv-az95-172:40924] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7efc73eae18b]
[fv-az95-172:40924] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7efc73e8d859]
[fv-az95-172:40924] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7efc74115911]
[fv-az95-172:40924] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7efc7412138c]
[fv-az95-172:40924] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7efc741213f7]
[fv-az95-172:40924] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7efc741216a9]
[fv-az95-172:40924] [ 7] plumed(+0xf47d)[0x56068e4be47d]
[fv-az95-172:40924] [ 8] plumed(+0x14004)[0x56068e4c3004]
[fv-az95-172:40924] [ 9] plumed(+0xf698)[0x56068e4be698]
[fv-az95-172:40924] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7efc73e8f0b3]
[fv-az95-172:40924] [11] plumed(+0xf76e)[0x56068e4be76e]
[fv-az95-172:40924] *** End of error message ***
</pre>
{% endraw %}
