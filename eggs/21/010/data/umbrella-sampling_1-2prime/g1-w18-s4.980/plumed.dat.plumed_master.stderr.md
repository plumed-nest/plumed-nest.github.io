**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w18-s4.980/plumed.dat   
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
[fv-az95-172:37617] *** Process received signal ***
[fv-az95-172:37617] Signal: Aborted (6)
[fv-az95-172:37617] Signal code:  (-6)
[fv-az95-172:37617] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3fd5ec5210]
[fv-az95-172:37617] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3fd5ec518b]
[fv-az95-172:37617] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3fd5ea4859]
[fv-az95-172:37617] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3fd612c911]
[fv-az95-172:37617] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f3fd613838c]
[fv-az95-172:37617] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f3fd61383f7]
[fv-az95-172:37617] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f3fd61386fd]
[fv-az95-172:37617] [ 7] plumed_master(+0xf5b5)[0x55f8d2a9a5b5]
[fv-az95-172:37617] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3fd5ea60b3]
[fv-az95-172:37617] [ 9] plumed_master(+0xf8be)[0x55f8d2a9a8be]
[fv-az95-172:37617] *** End of error message ***
</pre>
{% endraw %}
