**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w16-s7.338/plumed.dat   
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
[fv-az95-172:39823] *** Process received signal ***
[fv-az95-172:39823] Signal: Aborted (6)
[fv-az95-172:39823] Signal code:  (-6)
[fv-az95-172:39823] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa14191e210]
[fv-az95-172:39823] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa14191e18b]
[fv-az95-172:39823] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa1418fd859]
[fv-az95-172:39823] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa141b85911]
[fv-az95-172:39823] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa141b9138c]
[fv-az95-172:39823] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa141b913f7]
[fv-az95-172:39823] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa141b916a9]
[fv-az95-172:39823] [ 7] plumed(+0xf47d)[0x55f3b59d547d]
[fv-az95-172:39823] [ 8] plumed(+0x14004)[0x55f3b59da004]
[fv-az95-172:39823] [ 9] plumed(+0xf698)[0x55f3b59d5698]
[fv-az95-172:39823] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa1418ff0b3]
[fv-az95-172:39823] [11] plumed(+0xf76e)[0x55f3b59d576e]
[fv-az95-172:39823] *** End of error message ***
</pre>
{% endraw %}
