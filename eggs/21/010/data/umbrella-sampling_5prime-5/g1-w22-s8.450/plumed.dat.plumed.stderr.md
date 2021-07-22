**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w22-s8.450/plumed.dat   
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
[fv-az95-172:44784] *** Process received signal ***
[fv-az95-172:44784] Signal: Aborted (6)
[fv-az95-172:44784] Signal code:  (-6)
[fv-az95-172:44784] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe54a066210]
[fv-az95-172:44784] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe54a06618b]
[fv-az95-172:44784] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe54a045859]
[fv-az95-172:44784] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe54a2cd911]
[fv-az95-172:44784] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe54a2d938c]
[fv-az95-172:44784] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe54a2d93f7]
[fv-az95-172:44784] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fe54a2d96a9]
[fv-az95-172:44784] [ 7] plumed(+0xf47d)[0x55de5754947d]
[fv-az95-172:44784] [ 8] plumed(+0x14004)[0x55de5754e004]
[fv-az95-172:44784] [ 9] plumed(+0xf698)[0x55de57549698]
[fv-az95-172:44784] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe54a0470b3]
[fv-az95-172:44784] [11] plumed(+0xf76e)[0x55de5754976e]
[fv-az95-172:44784] *** End of error message ***
</pre>
{% endraw %}
