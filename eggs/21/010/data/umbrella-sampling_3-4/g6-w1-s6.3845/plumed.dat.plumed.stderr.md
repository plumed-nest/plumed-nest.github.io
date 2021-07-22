**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g6-w1-s6.3845/plumed.dat   
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
[fv-az95-172:41534] *** Process received signal ***
[fv-az95-172:41534] Signal: Aborted (6)
[fv-az95-172:41534] Signal code:  (-6)
[fv-az95-172:41534] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc33aee7210]
[fv-az95-172:41534] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc33aee718b]
[fv-az95-172:41534] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc33aec6859]
[fv-az95-172:41534] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc33b14e911]
[fv-az95-172:41534] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc33b15a38c]
[fv-az95-172:41534] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc33b15a3f7]
[fv-az95-172:41534] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc33b15a6a9]
[fv-az95-172:41534] [ 7] plumed(+0xf47d)[0x55bc3d5cf47d]
[fv-az95-172:41534] [ 8] plumed(+0x14004)[0x55bc3d5d4004]
[fv-az95-172:41534] [ 9] plumed(+0xf698)[0x55bc3d5cf698]
[fv-az95-172:41534] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc33aec80b3]
[fv-az95-172:41534] [11] plumed(+0xf76e)[0x55bc3d5cf76e]
[fv-az95-172:41534] *** End of error message ***
</pre>
{% endraw %}
