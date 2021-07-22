**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g4-w4-s10.045/plumed.dat   
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
[fv-az95-172:40558] *** Process received signal ***
[fv-az95-172:40558] Signal: Aborted (6)
[fv-az95-172:40558] Signal code:  (-6)
[fv-az95-172:40558] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa1a9162210]
[fv-az95-172:40558] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa1a916218b]
[fv-az95-172:40558] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa1a9141859]
[fv-az95-172:40558] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa1a93c9911]
[fv-az95-172:40558] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa1a93d538c]
[fv-az95-172:40558] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa1a93d53f7]
[fv-az95-172:40558] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa1a93d56a9]
[fv-az95-172:40558] [ 7] plumed(+0xf47d)[0x55c7ad9a547d]
[fv-az95-172:40558] [ 8] plumed(+0x14004)[0x55c7ad9aa004]
[fv-az95-172:40558] [ 9] plumed(+0xf698)[0x55c7ad9a5698]
[fv-az95-172:40558] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa1a91430b3]
[fv-az95-172:40558] [11] plumed(+0xf76e)[0x55c7ad9a576e]
[fv-az95-172:40558] *** End of error message ***
</pre>
{% endraw %}
