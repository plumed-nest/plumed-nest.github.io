**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w14-s4.116/plumed.dat   
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
[fv-az95-172:37511] *** Process received signal ***
[fv-az95-172:37511] Signal: Aborted (6)
[fv-az95-172:37511] Signal code:  (-6)
[fv-az95-172:37511] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f13c0ce2210]
[fv-az95-172:37511] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f13c0ce218b]
[fv-az95-172:37511] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f13c0cc1859]
[fv-az95-172:37511] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f13c0f49911]
[fv-az95-172:37511] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f13c0f5538c]
[fv-az95-172:37511] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f13c0f553f7]
[fv-az95-172:37511] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f13c0f556a9]
[fv-az95-172:37511] [ 7] plumed(+0xf47d)[0x5613613c447d]
[fv-az95-172:37511] [ 8] plumed(+0x14004)[0x5613613c9004]
[fv-az95-172:37511] [ 9] plumed(+0xf698)[0x5613613c4698]
[fv-az95-172:37511] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f13c0cc30b3]
[fv-az95-172:37511] [11] plumed(+0xf76e)[0x5613613c476e]
[fv-az95-172:37511] *** End of error message ***
</pre>
{% endraw %}
