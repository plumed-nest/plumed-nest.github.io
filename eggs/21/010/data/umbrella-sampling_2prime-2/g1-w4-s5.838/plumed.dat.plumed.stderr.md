**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w4-s5.838/plumed.dat   
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
[fv-az95-172:40092] *** Process received signal ***
[fv-az95-172:40092] Signal: Aborted (6)
[fv-az95-172:40092] Signal code:  (-6)
[fv-az95-172:40092] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f607493a210]
[fv-az95-172:40092] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f607493a18b]
[fv-az95-172:40092] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6074919859]
[fv-az95-172:40092] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6074ba1911]
[fv-az95-172:40092] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6074bad38c]
[fv-az95-172:40092] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6074bad3f7]
[fv-az95-172:40092] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f6074bad6a9]
[fv-az95-172:40092] [ 7] plumed(+0xf47d)[0x55886c4de47d]
[fv-az95-172:40092] [ 8] plumed(+0x14004)[0x55886c4e3004]
[fv-az95-172:40092] [ 9] plumed(+0xf698)[0x55886c4de698]
[fv-az95-172:40092] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f607491b0b3]
[fv-az95-172:40092] [11] plumed(+0xf76e)[0x55886c4de76e]
[fv-az95-172:40092] *** End of error message ***
</pre>
{% endraw %}
