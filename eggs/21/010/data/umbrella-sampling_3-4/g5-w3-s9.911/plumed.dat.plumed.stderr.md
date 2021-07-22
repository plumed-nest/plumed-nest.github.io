**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g5-w3-s9.911/plumed.dat   
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
[fv-az95-172:41510] *** Process received signal ***
[fv-az95-172:41510] Signal: Aborted (6)
[fv-az95-172:41510] Signal code:  (-6)
[fv-az95-172:41510] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f57c5fc1210]
[fv-az95-172:41510] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f57c5fc118b]
[fv-az95-172:41510] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f57c5fa0859]
[fv-az95-172:41510] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f57c6228911]
[fv-az95-172:41510] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f57c623438c]
[fv-az95-172:41510] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f57c62343f7]
[fv-az95-172:41510] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f57c62346a9]
[fv-az95-172:41510] [ 7] plumed(+0xf47d)[0x560da1ced47d]
[fv-az95-172:41510] [ 8] plumed(+0x14004)[0x560da1cf2004]
[fv-az95-172:41510] [ 9] plumed(+0xf698)[0x560da1ced698]
[fv-az95-172:41510] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f57c5fa20b3]
[fv-az95-172:41510] [11] plumed(+0xf76e)[0x560da1ced76e]
[fv-az95-172:41510] *** End of error message ***
</pre>
{% endraw %}
