**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g3-w6-s4.741/plumed.dat   
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
[fv-az95-172:40459] *** Process received signal ***
[fv-az95-172:40459] Signal: Aborted (6)
[fv-az95-172:40459] Signal code:  (-6)
[fv-az95-172:40459] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5146ede210]
[fv-az95-172:40459] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f5146ede18b]
[fv-az95-172:40459] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5146ebd859]
[fv-az95-172:40459] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f5147145911]
[fv-az95-172:40459] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f514715138c]
[fv-az95-172:40459] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f51471513f7]
[fv-az95-172:40459] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f51471516a9]
[fv-az95-172:40459] [ 7] plumed(+0xf47d)[0x55a59fdd947d]
[fv-az95-172:40459] [ 8] plumed(+0x14004)[0x55a59fdde004]
[fv-az95-172:40459] [ 9] plumed(+0xf698)[0x55a59fdd9698]
[fv-az95-172:40459] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f5146ebf0b3]
[fv-az95-172:40459] [11] plumed(+0xf76e)[0x55a59fdd976e]
[fv-az95-172:40459] *** End of error message ***
</pre>
{% endraw %}
