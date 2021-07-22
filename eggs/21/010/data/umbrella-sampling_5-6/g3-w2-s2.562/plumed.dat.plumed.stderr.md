**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g3-w2-s2.562/plumed.dat   
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
[fv-az95-172:44217] *** Process received signal ***
[fv-az95-172:44217] Signal: Aborted (6)
[fv-az95-172:44217] Signal code:  (-6)
[fv-az95-172:44217] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f02771d4210]
[fv-az95-172:44217] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f02771d418b]
[fv-az95-172:44217] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f02771b3859]
[fv-az95-172:44217] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f027743b911]
[fv-az95-172:44217] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f027744738c]
[fv-az95-172:44217] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f02774473f7]
[fv-az95-172:44217] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f02774476a9]
[fv-az95-172:44217] [ 7] plumed(+0xf47d)[0x561f3dbb847d]
[fv-az95-172:44217] [ 8] plumed(+0x14004)[0x561f3dbbd004]
[fv-az95-172:44217] [ 9] plumed(+0xf698)[0x561f3dbb8698]
[fv-az95-172:44217] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f02771b50b3]
[fv-az95-172:44217] [11] plumed(+0xf76e)[0x561f3dbb876e]
[fv-az95-172:44217] *** End of error message ***
</pre>
{% endraw %}
