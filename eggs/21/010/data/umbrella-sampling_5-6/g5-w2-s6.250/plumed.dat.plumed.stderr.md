**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g5-w2-s6.250/plumed.dat   
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
[fv-az95-172:44314] *** Process received signal ***
[fv-az95-172:44314] Signal: Aborted (6)
[fv-az95-172:44314] Signal code:  (-6)
[fv-az95-172:44314] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f18d4de6210]
[fv-az95-172:44314] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f18d4de618b]
[fv-az95-172:44314] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f18d4dc5859]
[fv-az95-172:44314] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f18d504d911]
[fv-az95-172:44314] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f18d505938c]
[fv-az95-172:44314] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f18d50593f7]
[fv-az95-172:44314] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f18d50596a9]
[fv-az95-172:44314] [ 7] plumed(+0xf47d)[0x55c91966247d]
[fv-az95-172:44314] [ 8] plumed(+0x14004)[0x55c919667004]
[fv-az95-172:44314] [ 9] plumed(+0xf698)[0x55c919662698]
[fv-az95-172:44314] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f18d4dc70b3]
[fv-az95-172:44314] [11] plumed(+0xf76e)[0x55c91966276e]
[fv-az95-172:44314] *** End of error message ***
</pre>
{% endraw %}
