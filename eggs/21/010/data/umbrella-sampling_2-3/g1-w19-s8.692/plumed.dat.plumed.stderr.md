**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w19-s8.692/plumed.dat   
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
[fv-az95-172:39035] *** Process received signal ***
[fv-az95-172:39035] Signal: Aborted (6)
[fv-az95-172:39035] Signal code:  (-6)
[fv-az95-172:39035] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa65e89c210]
[fv-az95-172:39035] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa65e89c18b]
[fv-az95-172:39035] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa65e87b859]
[fv-az95-172:39035] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa65eb03911]
[fv-az95-172:39035] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa65eb0f38c]
[fv-az95-172:39035] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa65eb0f3f7]
[fv-az95-172:39035] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa65eb0f6a9]
[fv-az95-172:39035] [ 7] plumed(+0xf47d)[0x556eac93f47d]
[fv-az95-172:39035] [ 8] plumed(+0x14004)[0x556eac944004]
[fv-az95-172:39035] [ 9] plumed(+0xf698)[0x556eac93f698]
[fv-az95-172:39035] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa65e87d0b3]
[fv-az95-172:39035] [11] plumed(+0xf76e)[0x556eac93f76e]
[fv-az95-172:39035] *** End of error message ***
</pre>
{% endraw %}
