**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g3-w1-s3.324/plumed.dat   
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
[fv-az95-172:38652] *** Process received signal ***
[fv-az95-172:38652] Signal: Aborted (6)
[fv-az95-172:38652] Signal code:  (-6)
[fv-az95-172:38652] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f48194be210]
[fv-az95-172:38652] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f48194be18b]
[fv-az95-172:38652] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f481949d859]
[fv-az95-172:38652] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4819725911]
[fv-az95-172:38652] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f481973138c]
[fv-az95-172:38652] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f48197313f7]
[fv-az95-172:38652] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f48197316fd]
[fv-az95-172:38652] [ 7] plumed_master(+0xf5b5)[0x5621499335b5]
[fv-az95-172:38652] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f481949f0b3]
[fv-az95-172:38652] [ 9] plumed_master(+0xf8be)[0x5621499338be]
[fv-az95-172:38652] *** End of error message ***
</pre>
{% endraw %}
