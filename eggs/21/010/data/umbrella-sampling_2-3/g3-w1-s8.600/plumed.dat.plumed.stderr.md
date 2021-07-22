**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g3-w1-s8.600/plumed.dat   
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
[fv-az95-172:39624] *** Process received signal ***
[fv-az95-172:39624] Signal: Aborted (6)
[fv-az95-172:39624] Signal code:  (-6)
[fv-az95-172:39624] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa90a0c4210]
[fv-az95-172:39624] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa90a0c418b]
[fv-az95-172:39624] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa90a0a3859]
[fv-az95-172:39624] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa90a32b911]
[fv-az95-172:39624] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa90a33738c]
[fv-az95-172:39624] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa90a3373f7]
[fv-az95-172:39624] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fa90a3376a9]
[fv-az95-172:39624] [ 7] plumed(+0xf47d)[0x563dfb35447d]
[fv-az95-172:39624] [ 8] plumed(+0x14004)[0x563dfb359004]
[fv-az95-172:39624] [ 9] plumed(+0xf698)[0x563dfb354698]
[fv-az95-172:39624] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa90a0a50b3]
[fv-az95-172:39624] [11] plumed(+0xf76e)[0x563dfb35476e]
[fv-az95-172:39624] *** End of error message ***
</pre>
{% endraw %}
