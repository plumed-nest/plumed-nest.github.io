**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w17-s6.950/plumed.dat   
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
[fv-az95-172:44638] *** Process received signal ***
[fv-az95-172:44638] Signal: Aborted (6)
[fv-az95-172:44638] Signal code:  (-6)
[fv-az95-172:44638] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc3a8c72210]
[fv-az95-172:44638] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc3a8c7218b]
[fv-az95-172:44638] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc3a8c51859]
[fv-az95-172:44638] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc3a8ed9911]
[fv-az95-172:44638] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc3a8ee538c]
[fv-az95-172:44638] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc3a8ee53f7]
[fv-az95-172:44638] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc3a8ee56a9]
[fv-az95-172:44638] [ 7] plumed(+0xf47d)[0x55b5165b047d]
[fv-az95-172:44638] [ 8] plumed(+0x14004)[0x55b5165b5004]
[fv-az95-172:44638] [ 9] plumed(+0xf698)[0x55b5165b0698]
[fv-az95-172:44638] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc3a8c530b3]
[fv-az95-172:44638] [11] plumed(+0xf76e)[0x55b5165b076e]
[fv-az95-172:44638] *** End of error message ***
</pre>
{% endraw %}
