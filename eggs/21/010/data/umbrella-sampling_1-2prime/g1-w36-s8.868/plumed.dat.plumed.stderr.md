**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w36-s8.868/plumed.dat   
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
[fv-az95-172:38099] *** Process received signal ***
[fv-az95-172:38099] Signal: Aborted (6)
[fv-az95-172:38099] Signal code:  (-6)
[fv-az95-172:38099] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6fa309c210]
[fv-az95-172:38099] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f6fa309c18b]
[fv-az95-172:38099] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6fa307b859]
[fv-az95-172:38099] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6fa3303911]
[fv-az95-172:38099] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6fa330f38c]
[fv-az95-172:38099] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6fa330f3f7]
[fv-az95-172:38099] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f6fa330f6a9]
[fv-az95-172:38099] [ 7] plumed(+0xf47d)[0x555fc291947d]
[fv-az95-172:38099] [ 8] plumed(+0x14004)[0x555fc291e004]
[fv-az95-172:38099] [ 9] plumed(+0xf698)[0x555fc2919698]
[fv-az95-172:38099] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f6fa307d0b3]
[fv-az95-172:38099] [11] plumed(+0xf76e)[0x555fc291976e]
[fv-az95-172:38099] *** End of error message ***
</pre>
{% endraw %}
