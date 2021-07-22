**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w26-s9.650/plumed.dat   
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
[fv-az95-172:44882] *** Process received signal ***
[fv-az95-172:44882] Signal: Aborted (6)
[fv-az95-172:44882] Signal code:  (-6)
[fv-az95-172:44882] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fd4052a9210]
[fv-az95-172:44882] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fd4052a918b]
[fv-az95-172:44882] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fd405288859]
[fv-az95-172:44882] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fd405510911]
[fv-az95-172:44882] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fd40551c38c]
[fv-az95-172:44882] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fd40551c3f7]
[fv-az95-172:44882] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fd40551c6a9]
[fv-az95-172:44882] [ 7] plumed(+0xf47d)[0x5566e7ef647d]
[fv-az95-172:44882] [ 8] plumed(+0x14004)[0x5566e7efb004]
[fv-az95-172:44882] [ 9] plumed(+0xf698)[0x5566e7ef6698]
[fv-az95-172:44882] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fd40528a0b3]
[fv-az95-172:44882] [11] plumed(+0xf76e)[0x5566e7ef676e]
[fv-az95-172:44882] *** End of error message ***
</pre>
{% endraw %}
