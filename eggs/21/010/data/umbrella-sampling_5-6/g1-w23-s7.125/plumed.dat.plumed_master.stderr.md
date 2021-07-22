**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w23-s7.125/plumed.dat   
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
[fv-az95-172:43586] *** Process received signal ***
[fv-az95-172:43586] Signal: Aborted (6)
[fv-az95-172:43586] Signal code:  (-6)
[fv-az95-172:43586] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb6c3ef6210]
[fv-az95-172:43586] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb6c3ef618b]
[fv-az95-172:43586] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb6c3ed5859]
[fv-az95-172:43586] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb6c415d911]
[fv-az95-172:43586] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb6c416938c]
[fv-az95-172:43586] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb6c41693f7]
[fv-az95-172:43586] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fb6c41696fd]
[fv-az95-172:43586] [ 7] plumed_master(+0xf5b5)[0x561557e585b5]
[fv-az95-172:43586] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb6c3ed70b3]
[fv-az95-172:43586] [ 9] plumed_master(+0xf8be)[0x561557e588be]
[fv-az95-172:43586] *** End of error message ***
</pre>
{% endraw %}
