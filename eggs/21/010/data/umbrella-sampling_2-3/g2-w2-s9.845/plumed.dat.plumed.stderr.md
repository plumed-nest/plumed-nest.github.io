**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g2-w2-s9.845/plumed.dat   
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
[fv-az95-172:39551] *** Process received signal ***
[fv-az95-172:39551] Signal: Aborted (6)
[fv-az95-172:39551] Signal code:  (-6)
[fv-az95-172:39551] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0489a0b210]
[fv-az95-172:39551] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0489a0b18b]
[fv-az95-172:39551] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f04899ea859]
[fv-az95-172:39551] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0489c72911]
[fv-az95-172:39551] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0489c7e38c]
[fv-az95-172:39551] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0489c7e3f7]
[fv-az95-172:39551] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0489c7e6a9]
[fv-az95-172:39551] [ 7] plumed(+0xf47d)[0x55a7020c647d]
[fv-az95-172:39551] [ 8] plumed(+0x14004)[0x55a7020cb004]
[fv-az95-172:39551] [ 9] plumed(+0xf698)[0x55a7020c6698]
[fv-az95-172:39551] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f04899ec0b3]
[fv-az95-172:39551] [11] plumed(+0xf76e)[0x55a7020c676e]
[fv-az95-172:39551] *** End of error message ***
</pre>
{% endraw %}
