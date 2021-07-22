**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w2-s3.139/plumed.dat   
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
[fv-az95-172:40948] *** Process received signal ***
[fv-az95-172:40948] Signal: Aborted (6)
[fv-az95-172:40948] Signal code:  (-6)
[fv-az95-172:40948] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f10f33ae210]
[fv-az95-172:40948] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f10f33ae18b]
[fv-az95-172:40948] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f10f338d859]
[fv-az95-172:40948] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f10f3615911]
[fv-az95-172:40948] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f10f362138c]
[fv-az95-172:40948] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f10f36213f7]
[fv-az95-172:40948] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f10f36216a9]
[fv-az95-172:40948] [ 7] plumed(+0xf47d)[0x563a1366747d]
[fv-az95-172:40948] [ 8] plumed(+0x14004)[0x563a1366c004]
[fv-az95-172:40948] [ 9] plumed(+0xf698)[0x563a13667698]
[fv-az95-172:40948] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f10f338f0b3]
[fv-az95-172:40948] [11] plumed(+0xf76e)[0x563a1366776e]
[fv-az95-172:40948] *** End of error message ***
</pre>
{% endraw %}
