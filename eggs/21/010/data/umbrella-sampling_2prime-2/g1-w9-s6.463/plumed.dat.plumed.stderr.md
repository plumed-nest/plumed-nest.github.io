**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w9-s6.463/plumed.dat   
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
[fv-az95-172:40214] *** Process received signal ***
[fv-az95-172:40214] Signal: Aborted (6)
[fv-az95-172:40214] Signal code:  (-6)
[fv-az95-172:40214] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff62c8b0210]
[fv-az95-172:40214] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff62c8b018b]
[fv-az95-172:40214] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff62c88f859]
[fv-az95-172:40214] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff62cb17911]
[fv-az95-172:40214] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff62cb2338c]
[fv-az95-172:40214] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff62cb233f7]
[fv-az95-172:40214] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ff62cb236a9]
[fv-az95-172:40214] [ 7] plumed(+0xf47d)[0x564f4e9bb47d]
[fv-az95-172:40214] [ 8] plumed(+0x14004)[0x564f4e9c0004]
[fv-az95-172:40214] [ 9] plumed(+0xf698)[0x564f4e9bb698]
[fv-az95-172:40214] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff62c8910b3]
[fv-az95-172:40214] [11] plumed(+0xf76e)[0x564f4e9bb76e]
[fv-az95-172:40214] *** End of error message ***
</pre>
{% endraw %}
