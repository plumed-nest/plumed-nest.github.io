**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g1-w1-s2.250/plumed.dat   
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
[fv-az95-172:40631] *** Process received signal ***
[fv-az95-172:40631] Signal: Aborted (6)
[fv-az95-172:40631] Signal code:  (-6)
[fv-az95-172:40631] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fca9081f210]
[fv-az95-172:40631] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fca9081f18b]
[fv-az95-172:40631] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fca907fe859]
[fv-az95-172:40631] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fca90a86911]
[fv-az95-172:40631] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fca90a9238c]
[fv-az95-172:40631] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fca90a923f7]
[fv-az95-172:40631] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fca90a926a9]
[fv-az95-172:40631] [ 7] plumed(+0xf47d)[0x55bec52c747d]
[fv-az95-172:40631] [ 8] plumed(+0x14004)[0x55bec52cc004]
[fv-az95-172:40631] [ 9] plumed(+0xf698)[0x55bec52c7698]
[fv-az95-172:40631] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fca908000b3]
[fv-az95-172:40631] [11] plumed(+0xf76e)[0x55bec52c776e]
[fv-az95-172:40631] *** End of error message ***
</pre>
{% endraw %}
