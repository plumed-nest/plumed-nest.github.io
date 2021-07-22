**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5prime-5/g1-w10-s4.850/plumed.dat   
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
[fv-az95-172:44465] *** Process received signal ***
[fv-az95-172:44465] Signal: Aborted (6)
[fv-az95-172:44465] Signal code:  (-6)
[fv-az95-172:44465] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f601e132210]
[fv-az95-172:44465] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f601e13218b]
[fv-az95-172:44465] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f601e111859]
[fv-az95-172:44465] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f601e399911]
[fv-az95-172:44465] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f601e3a538c]
[fv-az95-172:44465] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f601e3a53f7]
[fv-az95-172:44465] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f601e3a56a9]
[fv-az95-172:44465] [ 7] plumed(+0xf47d)[0x563f2563a47d]
[fv-az95-172:44465] [ 8] plumed(+0x14004)[0x563f2563f004]
[fv-az95-172:44465] [ 9] plumed(+0xf698)[0x563f2563a698]
[fv-az95-172:44465] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f601e1130b3]
[fv-az95-172:44465] [11] plumed(+0xf76e)[0x563f2563a76e]
[fv-az95-172:44465] *** End of error message ***
</pre>
{% endraw %}
