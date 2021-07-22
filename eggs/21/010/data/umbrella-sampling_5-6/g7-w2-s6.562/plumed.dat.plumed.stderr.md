**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g7-w2-s6.562/plumed.dat   
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
[fv-az95-172:44413] *** Process received signal ***
[fv-az95-172:44413] Signal: Aborted (6)
[fv-az95-172:44413] Signal code:  (-6)
[fv-az95-172:44413] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f76382a2210]
[fv-az95-172:44413] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f76382a218b]
[fv-az95-172:44413] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7638281859]
[fv-az95-172:44413] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f7638509911]
[fv-az95-172:44413] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f763851538c]
[fv-az95-172:44413] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f76385153f7]
[fv-az95-172:44413] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f76385156a9]
[fv-az95-172:44413] [ 7] plumed(+0xf47d)[0x5576f37e247d]
[fv-az95-172:44413] [ 8] plumed(+0x14004)[0x5576f37e7004]
[fv-az95-172:44413] [ 9] plumed(+0xf698)[0x5576f37e2698]
[fv-az95-172:44413] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f76382830b3]
[fv-az95-172:44413] [11] plumed(+0xf76e)[0x5576f37e276e]
[fv-az95-172:44413] *** End of error message ***
</pre>
{% endraw %}
