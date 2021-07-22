**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w9-s3.036/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: HILLS RESTART HEIGHT 0.000 W_STRIDE 50
Maybe a missing space or a typo?
[fv-az95-172:38603] *** Process received signal ***
[fv-az95-172:38603] Signal: Aborted (6)
[fv-az95-172:38603] Signal code:  (-6)
[fv-az95-172:38603] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fbe9f02f210]
[fv-az95-172:38603] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fbe9f02f18b]
[fv-az95-172:38603] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fbe9f00e859]
[fv-az95-172:38603] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fbe9f296911]
[fv-az95-172:38603] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fbe9f2a238c]
[fv-az95-172:38603] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fbe9f2a23f7]
[fv-az95-172:38603] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fbe9f2a26fd]
[fv-az95-172:38603] [ 7] plumed_master(+0xf5b5)[0x55bad124f5b5]
[fv-az95-172:38603] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fbe9f0100b3]
[fv-az95-172:38603] [ 9] plumed_master(+0xf8be)[0x55bad124f8be]
[fv-az95-172:38603] *** End of error message ***
</pre>
{% endraw %}
