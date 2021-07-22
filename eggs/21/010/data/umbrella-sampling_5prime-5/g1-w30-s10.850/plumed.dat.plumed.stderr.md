**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w30-s10.850/plumed.dat   
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
[fv-az95-172:45006] *** Process received signal ***
[fv-az95-172:45006] Signal: Aborted (6)
[fv-az95-172:45006] Signal code:  (-6)
[fv-az95-172:45006] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2df05b2210]
[fv-az95-172:45006] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2df05b218b]
[fv-az95-172:45006] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2df0591859]
[fv-az95-172:45006] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2df0819911]
[fv-az95-172:45006] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2df082538c]
[fv-az95-172:45006] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2df08253f7]
[fv-az95-172:45006] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f2df08256a9]
[fv-az95-172:45006] [ 7] plumed(+0xf47d)[0x55904efe047d]
[fv-az95-172:45006] [ 8] plumed(+0x14004)[0x55904efe5004]
[fv-az95-172:45006] [ 9] plumed(+0xf698)[0x55904efe0698]
[fv-az95-172:45006] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2df05930b3]
[fv-az95-172:45006] [11] plumed(+0xf76e)[0x55904efe076e]
[fv-az95-172:45006] *** End of error message ***
</pre>
{% endraw %}
