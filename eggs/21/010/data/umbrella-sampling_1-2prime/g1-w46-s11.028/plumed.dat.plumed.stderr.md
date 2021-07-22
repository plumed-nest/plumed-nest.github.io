**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w46-s11.028/plumed.dat   
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
[fv-az95-172:38371] *** Process received signal ***
[fv-az95-172:38371] Signal: Aborted (6)
[fv-az95-172:38371] Signal code:  (-6)
[fv-az95-172:38371] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb7f1f8a210]
[fv-az95-172:38371] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb7f1f8a18b]
[fv-az95-172:38371] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb7f1f69859]
[fv-az95-172:38371] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb7f21f1911]
[fv-az95-172:38371] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb7f21fd38c]
[fv-az95-172:38371] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb7f21fd3f7]
[fv-az95-172:38371] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fb7f21fd6a9]
[fv-az95-172:38371] [ 7] plumed(+0xf47d)[0x55c88672947d]
[fv-az95-172:38371] [ 8] plumed(+0x14004)[0x55c88672e004]
[fv-az95-172:38371] [ 9] plumed(+0xf698)[0x55c886729698]
[fv-az95-172:38371] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb7f1f6b0b3]
[fv-az95-172:38371] [11] plumed(+0xf76e)[0x55c88672976e]
[fv-az95-172:38371] *** End of error message ***
</pre>
{% endraw %}
