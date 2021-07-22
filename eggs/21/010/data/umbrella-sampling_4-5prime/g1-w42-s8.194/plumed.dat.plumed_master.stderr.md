**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w42-s8.194/plumed.dat   
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
[fv-az95-172:42505] *** Process received signal ***
[fv-az95-172:42505] Signal: Aborted (6)
[fv-az95-172:42505] Signal code:  (-6)
[fv-az95-172:42505] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb39aaa9210]
[fv-az95-172:42505] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb39aaa918b]
[fv-az95-172:42505] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb39aa88859]
[fv-az95-172:42505] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb39ad10911]
[fv-az95-172:42505] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb39ad1c38c]
[fv-az95-172:42505] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb39ad1c3f7]
[fv-az95-172:42505] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fb39ad1c6fd]
[fv-az95-172:42505] [ 7] plumed_master(+0xf5b5)[0x55a6985735b5]
[fv-az95-172:42505] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb39aa8a0b3]
[fv-az95-172:42505] [ 9] plumed_master(+0xf8be)[0x55a6985738be]
[fv-az95-172:42505] *** End of error message ***
</pre>
{% endraw %}
