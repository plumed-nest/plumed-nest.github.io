**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w25-s6.492/plumed.dat   
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
[fv-az95-172:37805] *** Process received signal ***
[fv-az95-172:37805] Signal: Aborted (6)
[fv-az95-172:37805] Signal code:  (-6)
[fv-az95-172:37805] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0a7e4d5210]
[fv-az95-172:37805] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0a7e4d518b]
[fv-az95-172:37805] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0a7e4b4859]
[fv-az95-172:37805] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0a7e73c911]
[fv-az95-172:37805] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0a7e74838c]
[fv-az95-172:37805] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0a7e7483f7]
[fv-az95-172:37805] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0a7e7486a9]
[fv-az95-172:37805] [ 7] plumed(+0xf47d)[0x55f91093247d]
[fv-az95-172:37805] [ 8] plumed(+0x14004)[0x55f910937004]
[fv-az95-172:37805] [ 9] plumed(+0xf698)[0x55f910932698]
[fv-az95-172:37805] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0a7e4b60b3]
[fv-az95-172:37805] [11] plumed(+0xf76e)[0x55f91093276e]
[fv-az95-172:37805] *** End of error message ***
</pre>
{% endraw %}
