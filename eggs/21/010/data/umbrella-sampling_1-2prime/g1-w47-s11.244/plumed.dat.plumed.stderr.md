**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w47-s11.244/plumed.dat   
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
[fv-az95-172:38396] *** Process received signal ***
[fv-az95-172:38396] Signal: Aborted (6)
[fv-az95-172:38396] Signal code:  (-6)
[fv-az95-172:38396] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5fb2332210]
[fv-az95-172:38396] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f5fb233218b]
[fv-az95-172:38396] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5fb2311859]
[fv-az95-172:38396] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f5fb2599911]
[fv-az95-172:38396] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f5fb25a538c]
[fv-az95-172:38396] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f5fb25a53f7]
[fv-az95-172:38396] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f5fb25a56a9]
[fv-az95-172:38396] [ 7] plumed(+0xf47d)[0x55e66447547d]
[fv-az95-172:38396] [ 8] plumed(+0x14004)[0x55e66447a004]
[fv-az95-172:38396] [ 9] plumed(+0xf698)[0x55e664475698]
[fv-az95-172:38396] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f5fb23130b3]
[fv-az95-172:38396] [11] plumed(+0xf76e)[0x55e66447576e]
[fv-az95-172:38396] *** End of error message ***
</pre>
{% endraw %}
