**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w9-s4.957/plumed.dat   
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
[fv-az95-172:41291] *** Process received signal ***
[fv-az95-172:41291] Signal: Aborted (6)
[fv-az95-172:41291] Signal code:  (-6)
[fv-az95-172:41291] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f8e42ba9210]
[fv-az95-172:41291] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f8e42ba918b]
[fv-az95-172:41291] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f8e42b88859]
[fv-az95-172:41291] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f8e42e10911]
[fv-az95-172:41291] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f8e42e1c38c]
[fv-az95-172:41291] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f8e42e1c3f7]
[fv-az95-172:41291] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f8e42e1c6a9]
[fv-az95-172:41291] [ 7] plumed(+0xf47d)[0x55aa447c547d]
[fv-az95-172:41291] [ 8] plumed(+0x14004)[0x55aa447ca004]
[fv-az95-172:41291] [ 9] plumed(+0xf698)[0x55aa447c5698]
[fv-az95-172:41291] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f8e42b8a0b3]
[fv-az95-172:41291] [11] plumed(+0xf76e)[0x55aa447c576e]
[fv-az95-172:41291] *** End of error message ***
</pre>
{% endraw %}
