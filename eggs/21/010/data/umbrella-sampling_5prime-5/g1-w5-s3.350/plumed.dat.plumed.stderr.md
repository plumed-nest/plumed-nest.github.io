**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w5-s3.350/plumed.dat   
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
[fv-az95-172:45057] *** Process received signal ***
[fv-az95-172:45057] Signal: Aborted (6)
[fv-az95-172:45057] Signal code:  (-6)
[fv-az95-172:45057] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fd8715fb210]
[fv-az95-172:45057] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fd8715fb18b]
[fv-az95-172:45057] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fd8715da859]
[fv-az95-172:45057] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fd871862911]
[fv-az95-172:45057] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fd87186e38c]
[fv-az95-172:45057] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fd87186e3f7]
[fv-az95-172:45057] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fd87186e6a9]
[fv-az95-172:45057] [ 7] plumed(+0xf47d)[0x558a0dc3947d]
[fv-az95-172:45057] [ 8] plumed(+0x14004)[0x558a0dc3e004]
[fv-az95-172:45057] [ 9] plumed(+0xf698)[0x558a0dc39698]
[fv-az95-172:45057] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fd8715dc0b3]
[fv-az95-172:45057] [11] plumed(+0xf76e)[0x558a0dc3976e]
[fv-az95-172:45057] *** End of error message ***
</pre>
{% endraw %}
