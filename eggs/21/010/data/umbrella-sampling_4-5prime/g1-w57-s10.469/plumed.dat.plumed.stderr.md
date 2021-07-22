**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w57-s10.469/plumed.dat   
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
[fv-az95-172:42888] *** Process received signal ***
[fv-az95-172:42888] Signal: Aborted (6)
[fv-az95-172:42888] Signal code:  (-6)
[fv-az95-172:42888] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff009b30210]
[fv-az95-172:42888] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff009b3018b]
[fv-az95-172:42888] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff009b0f859]
[fv-az95-172:42888] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff009d97911]
[fv-az95-172:42888] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff009da338c]
[fv-az95-172:42888] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff009da33f7]
[fv-az95-172:42888] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ff009da36a9]
[fv-az95-172:42888] [ 7] plumed(+0xf47d)[0x55cc1e1cb47d]
[fv-az95-172:42888] [ 8] plumed(+0x14004)[0x55cc1e1d0004]
[fv-az95-172:42888] [ 9] plumed(+0xf698)[0x55cc1e1cb698]
[fv-az95-172:42888] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff009b110b3]
[fv-az95-172:42888] [11] plumed(+0xf76e)[0x55cc1e1cb76e]
[fv-az95-172:42888] *** End of error message ***
</pre>
{% endraw %}
