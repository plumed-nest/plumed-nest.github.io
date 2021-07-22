**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g4-w2-s9.562/plumed.dat   
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
[fv-az95-172:44266] *** Process received signal ***
[fv-az95-172:44266] Signal: Aborted (6)
[fv-az95-172:44266] Signal code:  (-6)
[fv-az95-172:44266] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fbd563b4210]
[fv-az95-172:44266] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fbd563b418b]
[fv-az95-172:44266] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fbd56393859]
[fv-az95-172:44266] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fbd5661b911]
[fv-az95-172:44266] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fbd5662738c]
[fv-az95-172:44266] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fbd566273f7]
[fv-az95-172:44266] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fbd566276a9]
[fv-az95-172:44266] [ 7] plumed(+0xf47d)[0x5643d278747d]
[fv-az95-172:44266] [ 8] plumed(+0x14004)[0x5643d278c004]
[fv-az95-172:44266] [ 9] plumed(+0xf698)[0x5643d2787698]
[fv-az95-172:44266] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fbd563950b3]
[fv-az95-172:44266] [11] plumed(+0xf76e)[0x5643d278776e]
[fv-az95-172:44266] *** End of error message ***
</pre>
{% endraw %}
