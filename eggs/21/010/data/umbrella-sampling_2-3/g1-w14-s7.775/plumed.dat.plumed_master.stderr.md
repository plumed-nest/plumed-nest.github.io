**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w14-s7.775/plumed.dat   
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
[fv-az95-172:38922] *** Process received signal ***
[fv-az95-172:38922] Signal: Aborted (6)
[fv-az95-172:38922] Signal code:  (-6)
[fv-az95-172:38922] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fed131b0210]
[fv-az95-172:38922] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fed131b018b]
[fv-az95-172:38922] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fed1318f859]
[fv-az95-172:38922] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fed13417911]
[fv-az95-172:38922] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fed1342338c]
[fv-az95-172:38922] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fed134233f7]
[fv-az95-172:38922] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fed134236fd]
[fv-az95-172:38922] [ 7] plumed_master(+0xf5b5)[0x55b1652a25b5]
[fv-az95-172:38922] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fed131910b3]
[fv-az95-172:38922] [ 9] plumed_master(+0xf8be)[0x55b1652a28be]
[fv-az95-172:38922] *** End of error message ***
</pre>
{% endraw %}
