**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w45-s8.649/plumed.dat   
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
[fv-az95-172:42570] *** Process received signal ***
[fv-az95-172:42570] Signal: Aborted (6)
[fv-az95-172:42570] Signal code:  (-6)
[fv-az95-172:42570] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc8b554c210]
[fv-az95-172:42570] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc8b554c18b]
[fv-az95-172:42570] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc8b552b859]
[fv-az95-172:42570] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc8b57b3911]
[fv-az95-172:42570] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc8b57bf38c]
[fv-az95-172:42570] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc8b57bf3f7]
[fv-az95-172:42570] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc8b57bf6a9]
[fv-az95-172:42570] [ 7] plumed(+0xf47d)[0x55f0bdd4d47d]
[fv-az95-172:42570] [ 8] plumed(+0x14004)[0x55f0bdd52004]
[fv-az95-172:42570] [ 9] plumed(+0xf698)[0x55f0bdd4d698]
[fv-az95-172:42570] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc8b552d0b3]
[fv-az95-172:42570] [11] plumed(+0xf76e)[0x55f0bdd4d76e]
[fv-az95-172:42570] *** End of error message ***
</pre>
{% endraw %}
