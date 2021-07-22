**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w42-s10.164/plumed.dat   
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
[fv-az95-172:38269] *** Process received signal ***
[fv-az95-172:38269] Signal: Aborted (6)
[fv-az95-172:38269] Signal code:  (-6)
[fv-az95-172:38269] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f94bc0a0210]
[fv-az95-172:38269] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f94bc0a018b]
[fv-az95-172:38269] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f94bc07f859]
[fv-az95-172:38269] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f94bc307911]
[fv-az95-172:38269] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f94bc31338c]
[fv-az95-172:38269] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f94bc3133f7]
[fv-az95-172:38269] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f94bc3136a9]
[fv-az95-172:38269] [ 7] plumed(+0xf47d)[0x55a704dc547d]
[fv-az95-172:38269] [ 8] plumed(+0x14004)[0x55a704dca004]
[fv-az95-172:38269] [ 9] plumed(+0xf698)[0x55a704dc5698]
[fv-az95-172:38269] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f94bc0810b3]
[fv-az95-172:38269] [11] plumed(+0xf76e)[0x55a704dc576e]
[fv-az95-172:38269] *** End of error message ***
</pre>
{% endraw %}
