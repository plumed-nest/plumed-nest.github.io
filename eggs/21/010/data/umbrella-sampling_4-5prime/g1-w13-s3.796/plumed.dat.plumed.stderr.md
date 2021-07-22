**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w13-s3.796/plumed.dat   
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
[fv-az95-172:41707] *** Process received signal ***
[fv-az95-172:41707] Signal: Aborted (6)
[fv-az95-172:41707] Signal code:  (-6)
[fv-az95-172:41707] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6d67f66210]
[fv-az95-172:41707] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f6d67f6618b]
[fv-az95-172:41707] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6d67f45859]
[fv-az95-172:41707] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6d681cd911]
[fv-az95-172:41707] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6d681d938c]
[fv-az95-172:41707] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6d681d93f7]
[fv-az95-172:41707] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f6d681d96a9]
[fv-az95-172:41707] [ 7] plumed(+0xf47d)[0x55b7d074047d]
[fv-az95-172:41707] [ 8] plumed(+0x14004)[0x55b7d0745004]
[fv-az95-172:41707] [ 9] plumed(+0xf698)[0x55b7d0740698]
[fv-az95-172:41707] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f6d67f470b3]
[fv-az95-172:41707] [11] plumed(+0xf76e)[0x55b7d074076e]
[fv-az95-172:41707] *** End of error message ***
</pre>
{% endraw %}
