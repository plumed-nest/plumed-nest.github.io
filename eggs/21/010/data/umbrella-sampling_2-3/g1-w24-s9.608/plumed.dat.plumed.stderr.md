**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w24-s9.608/plumed.dat   
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
[fv-az95-172:39231] *** Process received signal ***
[fv-az95-172:39231] Signal: Aborted (6)
[fv-az95-172:39231] Signal code:  (-6)
[fv-az95-172:39231] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff2ce004210]
[fv-az95-172:39231] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff2ce00418b]
[fv-az95-172:39231] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff2cdfe3859]
[fv-az95-172:39231] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff2ce26b911]
[fv-az95-172:39231] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff2ce27738c]
[fv-az95-172:39231] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff2ce2773f7]
[fv-az95-172:39231] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7ff2ce2776a9]
[fv-az95-172:39231] [ 7] plumed(+0xf47d)[0x55babb2c747d]
[fv-az95-172:39231] [ 8] plumed(+0x14004)[0x55babb2cc004]
[fv-az95-172:39231] [ 9] plumed(+0xf698)[0x55babb2c7698]
[fv-az95-172:39231] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff2cdfe50b3]
[fv-az95-172:39231] [11] plumed(+0xf76e)[0x55babb2c776e]
[fv-az95-172:39231] *** End of error message ***
</pre>
{% endraw %}
