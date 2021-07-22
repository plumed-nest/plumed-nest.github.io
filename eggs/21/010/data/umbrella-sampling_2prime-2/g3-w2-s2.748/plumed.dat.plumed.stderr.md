**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g3-w2-s2.748/plumed.dat   
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
[fv-az95-172:40361] *** Process received signal ***
[fv-az95-172:40361] Signal: Aborted (6)
[fv-az95-172:40361] Signal code:  (-6)
[fv-az95-172:40361] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fbbb7792210]
[fv-az95-172:40361] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fbbb779218b]
[fv-az95-172:40361] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fbbb7771859]
[fv-az95-172:40361] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fbbb79f9911]
[fv-az95-172:40361] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fbbb7a0538c]
[fv-az95-172:40361] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fbbb7a053f7]
[fv-az95-172:40361] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fbbb7a056a9]
[fv-az95-172:40361] [ 7] plumed(+0xf47d)[0x559adeac647d]
[fv-az95-172:40361] [ 8] plumed(+0x14004)[0x559adeacb004]
[fv-az95-172:40361] [ 9] plumed(+0xf698)[0x559adeac6698]
[fv-az95-172:40361] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fbbb77730b3]
[fv-az95-172:40361] [11] plumed(+0xf76e)[0x559adeac676e]
[fv-az95-172:40361] *** End of error message ***
</pre>
{% endraw %}
