**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w13-s4.625/plumed.dat   
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
[fv-az95-172:43307] *** Process received signal ***
[fv-az95-172:43307] Signal: Aborted (6)
[fv-az95-172:43307] Signal code:  (-6)
[fv-az95-172:43307] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fab27638210]
[fv-az95-172:43307] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fab2763818b]
[fv-az95-172:43307] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fab27617859]
[fv-az95-172:43307] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fab2789f911]
[fv-az95-172:43307] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fab278ab38c]
[fv-az95-172:43307] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fab278ab3f7]
[fv-az95-172:43307] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fab278ab6a9]
[fv-az95-172:43307] [ 7] plumed(+0xf47d)[0x5556fc22e47d]
[fv-az95-172:43307] [ 8] plumed(+0x14004)[0x5556fc233004]
[fv-az95-172:43307] [ 9] plumed(+0xf698)[0x5556fc22e698]
[fv-az95-172:43307] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fab276190b3]
[fv-az95-172:43307] [11] plumed(+0xf76e)[0x5556fc22e76e]
[fv-az95-172:43307] *** End of error message ***
</pre>
{% endraw %}
