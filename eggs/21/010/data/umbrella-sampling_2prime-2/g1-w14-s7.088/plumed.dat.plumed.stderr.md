**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w14-s7.088/plumed.dat   
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
[fv-az95-172:39774] *** Process received signal ***
[fv-az95-172:39774] Signal: Aborted (6)
[fv-az95-172:39774] Signal code:  (-6)
[fv-az95-172:39774] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe8c27fa210]
[fv-az95-172:39774] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe8c27fa18b]
[fv-az95-172:39774] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe8c27d9859]
[fv-az95-172:39774] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe8c2a61911]
[fv-az95-172:39774] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe8c2a6d38c]
[fv-az95-172:39774] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe8c2a6d3f7]
[fv-az95-172:39774] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fe8c2a6d6a9]
[fv-az95-172:39774] [ 7] plumed(+0xf47d)[0x55e85d5bb47d]
[fv-az95-172:39774] [ 8] plumed(+0x14004)[0x55e85d5c0004]
[fv-az95-172:39774] [ 9] plumed(+0xf698)[0x55e85d5bb698]
[fv-az95-172:39774] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe8c27db0b3]
[fv-az95-172:39774] [11] plumed(+0xf76e)[0x55e85d5bb76e]
[fv-az95-172:39774] *** End of error message ***
</pre>
{% endraw %}
