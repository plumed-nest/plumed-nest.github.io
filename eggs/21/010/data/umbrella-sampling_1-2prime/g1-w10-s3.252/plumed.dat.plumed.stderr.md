**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w10-s3.252/plumed.dat   
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
[fv-az95-172:37410] *** Process received signal ***
[fv-az95-172:37410] Signal: Aborted (6)
[fv-az95-172:37410] Signal code:  (-6)
[fv-az95-172:37410] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f480eb28210]
[fv-az95-172:37410] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f480eb2818b]
[fv-az95-172:37410] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f480eb07859]
[fv-az95-172:37410] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f480ed8f911]
[fv-az95-172:37410] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f480ed9b38c]
[fv-az95-172:37410] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f480ed9b3f7]
[fv-az95-172:37410] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f480ed9b6a9]
[fv-az95-172:37410] [ 7] plumed(+0xf47d)[0x559142fa947d]
[fv-az95-172:37410] [ 8] plumed(+0x14004)[0x559142fae004]
[fv-az95-172:37410] [ 9] plumed(+0xf698)[0x559142fa9698]
[fv-az95-172:37410] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f480eb090b3]
[fv-az95-172:37410] [11] plumed(+0xf76e)[0x559142fa976e]
[fv-az95-172:37410] *** End of error message ***
</pre>
{% endraw %}
