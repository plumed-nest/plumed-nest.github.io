**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g3-w1-s3.1135/plumed.dat   
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
[fv-az95-172:43160] *** Process received signal ***
[fv-az95-172:43160] Signal: Aborted (6)
[fv-az95-172:43160] Signal code:  (-6)
[fv-az95-172:43160] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f051ab39210]
[fv-az95-172:43160] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f051ab3918b]
[fv-az95-172:43160] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f051ab18859]
[fv-az95-172:43160] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f051ada0911]
[fv-az95-172:43160] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f051adac38c]
[fv-az95-172:43160] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f051adac3f7]
[fv-az95-172:43160] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f051adac6a9]
[fv-az95-172:43160] [ 7] plumed(+0xf47d)[0x55e1b2c4547d]
[fv-az95-172:43160] [ 8] plumed(+0x14004)[0x55e1b2c4a004]
[fv-az95-172:43160] [ 9] plumed(+0xf698)[0x55e1b2c45698]
[fv-az95-172:43160] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f051ab1a0b3]
[fv-az95-172:43160] [11] plumed(+0xf76e)[0x55e1b2c4576e]
[fv-az95-172:43160] *** End of error message ***
</pre>
{% endraw %}
