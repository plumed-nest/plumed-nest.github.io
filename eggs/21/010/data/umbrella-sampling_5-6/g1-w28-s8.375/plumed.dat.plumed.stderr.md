**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w28-s8.375/plumed.dat   
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
[fv-az95-172:43699] *** Process received signal ***
[fv-az95-172:43699] Signal: Aborted (6)
[fv-az95-172:43699] Signal code:  (-6)
[fv-az95-172:43699] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f108d020210]
[fv-az95-172:43699] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f108d02018b]
[fv-az95-172:43699] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f108cfff859]
[fv-az95-172:43699] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f108d287911]
[fv-az95-172:43699] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f108d29338c]
[fv-az95-172:43699] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f108d2933f7]
[fv-az95-172:43699] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f108d2936a9]
[fv-az95-172:43699] [ 7] plumed(+0xf47d)[0x55c36a46c47d]
[fv-az95-172:43699] [ 8] plumed(+0x14004)[0x55c36a471004]
[fv-az95-172:43699] [ 9] plumed(+0xf698)[0x55c36a46c698]
[fv-az95-172:43699] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f108d0010b3]
[fv-az95-172:43699] [11] plumed(+0xf76e)[0x55c36a46c76e]
[fv-az95-172:43699] *** End of error message ***
</pre>
{% endraw %}
