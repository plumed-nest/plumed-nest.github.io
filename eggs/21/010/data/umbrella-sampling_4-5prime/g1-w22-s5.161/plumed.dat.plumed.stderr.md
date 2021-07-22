**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w22-s5.161/plumed.dat   
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
[fv-az95-172:41956] *** Process received signal ***
[fv-az95-172:41956] Signal: Aborted (6)
[fv-az95-172:41956] Signal code:  (-6)
[fv-az95-172:41956] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fd9cb1a7210]
[fv-az95-172:41956] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fd9cb1a718b]
[fv-az95-172:41956] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fd9cb186859]
[fv-az95-172:41956] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fd9cb40e911]
[fv-az95-172:41956] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fd9cb41a38c]
[fv-az95-172:41956] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fd9cb41a3f7]
[fv-az95-172:41956] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fd9cb41a6a9]
[fv-az95-172:41956] [ 7] plumed(+0xf47d)[0x55dfd234447d]
[fv-az95-172:41956] [ 8] plumed(+0x14004)[0x55dfd2349004]
[fv-az95-172:41956] [ 9] plumed(+0xf698)[0x55dfd2344698]
[fv-az95-172:41956] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fd9cb1880b3]
[fv-az95-172:41956] [11] plumed(+0xf76e)[0x55dfd234476e]
[fv-az95-172:41956] *** End of error message ***
</pre>
{% endraw %}
