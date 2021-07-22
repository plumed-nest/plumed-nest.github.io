**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w13-s5.750/plumed.dat   
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
[fv-az95-172:44538] *** Process received signal ***
[fv-az95-172:44538] Signal: Aborted (6)
[fv-az95-172:44538] Signal code:  (-6)
[fv-az95-172:44538] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5fc87bf210]
[fv-az95-172:44538] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f5fc87bf18b]
[fv-az95-172:44538] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5fc879e859]
[fv-az95-172:44538] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f5fc8a26911]
[fv-az95-172:44538] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f5fc8a3238c]
[fv-az95-172:44538] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f5fc8a323f7]
[fv-az95-172:44538] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f5fc8a326a9]
[fv-az95-172:44538] [ 7] plumed(+0xf47d)[0x559d54c0f47d]
[fv-az95-172:44538] [ 8] plumed(+0x14004)[0x559d54c14004]
[fv-az95-172:44538] [ 9] plumed(+0xf698)[0x559d54c0f698]
[fv-az95-172:44538] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f5fc87a00b3]
[fv-az95-172:44538] [11] plumed(+0xf76e)[0x559d54c0f76e]
[fv-az95-172:44538] *** End of error message ***
</pre>
{% endraw %}
