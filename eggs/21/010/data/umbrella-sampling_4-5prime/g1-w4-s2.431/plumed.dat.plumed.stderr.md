**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w4-s2.431/plumed.dat   
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
[fv-az95-172:42424] *** Process received signal ***
[fv-az95-172:42424] Signal: Aborted (6)
[fv-az95-172:42424] Signal code:  (-6)
[fv-az95-172:42424] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa65c24b210]
[fv-az95-172:42424] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa65c24b18b]
[fv-az95-172:42424] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa65c22a859]
[fv-az95-172:42424] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa65c4b2911]
[fv-az95-172:42424] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa65c4be38c]
[fv-az95-172:42424] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa65c4be3f7]
[fv-az95-172:42424] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa65c4be6a9]
[fv-az95-172:42424] [ 7] plumed(+0xf47d)[0x55649436947d]
[fv-az95-172:42424] [ 8] plumed(+0x14004)[0x55649436e004]
[fv-az95-172:42424] [ 9] plumed(+0xf698)[0x556494369698]
[fv-az95-172:42424] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa65c22c0b3]
[fv-az95-172:42424] [11] plumed(+0xf76e)[0x55649436976e]
[fv-az95-172:42424] *** End of error message ***
</pre>
{% endraw %}
