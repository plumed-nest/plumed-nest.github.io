**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w24-s8.338/plumed.dat   
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
[fv-az95-172:40043] *** Process received signal ***
[fv-az95-172:40043] Signal: Aborted (6)
[fv-az95-172:40043] Signal code:  (-6)
[fv-az95-172:40043] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb264620210]
[fv-az95-172:40043] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb26462018b]
[fv-az95-172:40043] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb2645ff859]
[fv-az95-172:40043] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb264887911]
[fv-az95-172:40043] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb26489338c]
[fv-az95-172:40043] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb2648933f7]
[fv-az95-172:40043] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fb2648936a9]
[fv-az95-172:40043] [ 7] plumed(+0xf47d)[0x55ba280db47d]
[fv-az95-172:40043] [ 8] plumed(+0x14004)[0x55ba280e0004]
[fv-az95-172:40043] [ 9] plumed(+0xf698)[0x55ba280db698]
[fv-az95-172:40043] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb2646010b3]
[fv-az95-172:40043] [11] plumed(+0xf76e)[0x55ba280db76e]
[fv-az95-172:40043] *** End of error message ***
</pre>
{% endraw %}
