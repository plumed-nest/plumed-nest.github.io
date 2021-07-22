**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w23-s8.213/plumed.dat   
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
[fv-az95-172:40019] *** Process received signal ***
[fv-az95-172:40019] Signal: Aborted (6)
[fv-az95-172:40019] Signal code:  (-6)
[fv-az95-172:40019] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f7ae1919210]
[fv-az95-172:40019] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f7ae191918b]
[fv-az95-172:40019] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7ae18f8859]
[fv-az95-172:40019] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f7ae1b80911]
[fv-az95-172:40019] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f7ae1b8c38c]
[fv-az95-172:40019] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f7ae1b8c3f7]
[fv-az95-172:40019] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f7ae1b8c6a9]
[fv-az95-172:40019] [ 7] plumed(+0xf47d)[0x55bfe940d47d]
[fv-az95-172:40019] [ 8] plumed(+0x14004)[0x55bfe9412004]
[fv-az95-172:40019] [ 9] plumed(+0xf698)[0x55bfe940d698]
[fv-az95-172:40019] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f7ae18fa0b3]
[fv-az95-172:40019] [11] plumed(+0xf76e)[0x55bfe940d76e]
[fv-az95-172:40019] *** End of error message ***
</pre>
{% endraw %}
