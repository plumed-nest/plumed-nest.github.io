**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w2-s5.575/plumed.dat   
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
[fv-az95-172:39109] *** Process received signal ***
[fv-az95-172:39109] Signal: Aborted (6)
[fv-az95-172:39109] Signal code:  (-6)
[fv-az95-172:39109] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe50520f210]
[fv-az95-172:39109] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe50520f18b]
[fv-az95-172:39109] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe5051ee859]
[fv-az95-172:39109] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe505476911]
[fv-az95-172:39109] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe50548238c]
[fv-az95-172:39109] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe5054823f7]
[fv-az95-172:39109] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fe5054826a9]
[fv-az95-172:39109] [ 7] plumed(+0xf47d)[0x563f5144747d]
[fv-az95-172:39109] [ 8] plumed(+0x14004)[0x563f5144c004]
[fv-az95-172:39109] [ 9] plumed(+0xf698)[0x563f51447698]
[fv-az95-172:39109] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe5051f00b3]
[fv-az95-172:39109] [11] plumed(+0xf76e)[0x563f5144776e]
[fv-az95-172:39109] *** End of error message ***
</pre>
{% endraw %}
