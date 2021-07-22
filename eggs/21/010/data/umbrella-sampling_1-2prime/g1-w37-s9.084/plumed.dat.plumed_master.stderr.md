**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w37-s9.084/plumed.dat   
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
[fv-az95-172:38132] *** Process received signal ***
[fv-az95-172:38132] Signal: Aborted (6)
[fv-az95-172:38132] Signal code:  (-6)
[fv-az95-172:38132] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6a8fe7f210]
[fv-az95-172:38132] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f6a8fe7f18b]
[fv-az95-172:38132] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6a8fe5e859]
[fv-az95-172:38132] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6a900e6911]
[fv-az95-172:38132] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6a900f238c]
[fv-az95-172:38132] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6a900f23f7]
[fv-az95-172:38132] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f6a900f26fd]
[fv-az95-172:38132] [ 7] plumed_master(+0xf5b5)[0x561e04dbc5b5]
[fv-az95-172:38132] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f6a8fe600b3]
[fv-az95-172:38132] [ 9] plumed_master(+0xf8be)[0x561e04dbc8be]
[fv-az95-172:38132] *** End of error message ***
</pre>
{% endraw %}
