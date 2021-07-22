**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w23-s9.425/plumed.dat   
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
[fv-az95-172:39207] *** Process received signal ***
[fv-az95-172:39207] Signal: Aborted (6)
[fv-az95-172:39207] Signal code:  (-6)
[fv-az95-172:39207] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe890029210]
[fv-az95-172:39207] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe89002918b]
[fv-az95-172:39207] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe890008859]
[fv-az95-172:39207] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe890290911]
[fv-az95-172:39207] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe89029c38c]
[fv-az95-172:39207] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe89029c3f7]
[fv-az95-172:39207] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fe89029c6a9]
[fv-az95-172:39207] [ 7] plumed(+0xf47d)[0x55bb66a9747d]
[fv-az95-172:39207] [ 8] plumed(+0x14004)[0x55bb66a9c004]
[fv-az95-172:39207] [ 9] plumed(+0xf698)[0x55bb66a97698]
[fv-az95-172:39207] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe89000a0b3]
[fv-az95-172:39207] [11] plumed(+0xf76e)[0x55bb66a9776e]
[fv-az95-172:39207] *** End of error message ***
</pre>
{% endraw %}
