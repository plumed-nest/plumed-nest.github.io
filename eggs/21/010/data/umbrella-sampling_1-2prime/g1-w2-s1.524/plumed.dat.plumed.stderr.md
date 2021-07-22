**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w2-s1.524/plumed.dat   
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
[fv-az95-172:37658] *** Process received signal ***
[fv-az95-172:37658] Signal: Aborted (6)
[fv-az95-172:37658] Signal code:  (-6)
[fv-az95-172:37658] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc133637210]
[fv-az95-172:37658] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc13363718b]
[fv-az95-172:37658] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc133616859]
[fv-az95-172:37658] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc13389e911]
[fv-az95-172:37658] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc1338aa38c]
[fv-az95-172:37658] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc1338aa3f7]
[fv-az95-172:37658] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc1338aa6a9]
[fv-az95-172:37658] [ 7] plumed(+0xf47d)[0x556251e2a47d]
[fv-az95-172:37658] [ 8] plumed(+0x14004)[0x556251e2f004]
[fv-az95-172:37658] [ 9] plumed(+0xf698)[0x556251e2a698]
[fv-az95-172:37658] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc1336180b3]
[fv-az95-172:37658] [11] plumed(+0xf76e)[0x556251e2a76e]
[fv-az95-172:37658] *** End of error message ***
</pre>
{% endraw %}
