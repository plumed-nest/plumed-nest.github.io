**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g5-w2-s9.734/plumed.dat   
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
[fv-az95-172:41486] *** Process received signal ***
[fv-az95-172:41486] Signal: Aborted (6)
[fv-az95-172:41486] Signal code:  (-6)
[fv-az95-172:41486] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f65c64d5210]
[fv-az95-172:41486] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f65c64d518b]
[fv-az95-172:41486] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f65c64b4859]
[fv-az95-172:41486] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f65c673c911]
[fv-az95-172:41486] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f65c674838c]
[fv-az95-172:41486] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f65c67483f7]
[fv-az95-172:41486] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f65c67486a9]
[fv-az95-172:41486] [ 7] plumed(+0xf47d)[0x55e4e590247d]
[fv-az95-172:41486] [ 8] plumed(+0x14004)[0x55e4e5907004]
[fv-az95-172:41486] [ 9] plumed(+0xf698)[0x55e4e5902698]
[fv-az95-172:41486] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f65c64b60b3]
[fv-az95-172:41486] [11] plumed(+0xf76e)[0x55e4e590276e]
[fv-az95-172:41486] *** End of error message ***
</pre>
{% endraw %}
