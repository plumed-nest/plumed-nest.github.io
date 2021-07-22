**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w27-s9.950/plumed.dat   
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
[fv-az95-172:44907] *** Process received signal ***
[fv-az95-172:44907] Signal: Aborted (6)
[fv-az95-172:44907] Signal code:  (-6)
[fv-az95-172:44907] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2b49576210]
[fv-az95-172:44907] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2b4957618b]
[fv-az95-172:44907] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2b49555859]
[fv-az95-172:44907] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2b497dd911]
[fv-az95-172:44907] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2b497e938c]
[fv-az95-172:44907] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2b497e93f7]
[fv-az95-172:44907] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f2b497e96a9]
[fv-az95-172:44907] [ 7] plumed(+0xf47d)[0x55680b8cd47d]
[fv-az95-172:44907] [ 8] plumed(+0x14004)[0x55680b8d2004]
[fv-az95-172:44907] [ 9] plumed(+0xf698)[0x55680b8cd698]
[fv-az95-172:44907] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2b495570b3]
[fv-az95-172:44907] [11] plumed(+0xf76e)[0x55680b8cd76e]
[fv-az95-172:44907] *** End of error message ***
</pre>
{% endraw %}
