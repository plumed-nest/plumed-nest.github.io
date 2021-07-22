**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w11-s4.125/plumed.dat   
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
[fv-az95-172:43257] *** Process received signal ***
[fv-az95-172:43257] Signal: Aborted (6)
[fv-az95-172:43257] Signal code:  (-6)
[fv-az95-172:43257] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f435dda8210]
[fv-az95-172:43257] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f435dda818b]
[fv-az95-172:43257] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f435dd87859]
[fv-az95-172:43257] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f435e00f911]
[fv-az95-172:43257] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f435e01b38c]
[fv-az95-172:43257] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f435e01b3f7]
[fv-az95-172:43257] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f435e01b6a9]
[fv-az95-172:43257] [ 7] plumed(+0xf47d)[0x560de3f5847d]
[fv-az95-172:43257] [ 8] plumed(+0x14004)[0x560de3f5d004]
[fv-az95-172:43257] [ 9] plumed(+0xf698)[0x560de3f58698]
[fv-az95-172:43257] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f435dd890b3]
[fv-az95-172:43257] [11] plumed(+0xf76e)[0x560de3f5876e]
[fv-az95-172:43257] *** End of error message ***
</pre>
{% endraw %}
