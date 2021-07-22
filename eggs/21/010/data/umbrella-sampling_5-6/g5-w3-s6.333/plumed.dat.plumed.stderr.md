**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g5-w3-s6.333/plumed.dat   
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
[fv-az95-172:44339] *** Process received signal ***
[fv-az95-172:44339] Signal: Aborted (6)
[fv-az95-172:44339] Signal code:  (-6)
[fv-az95-172:44339] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f48688d0210]
[fv-az95-172:44339] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f48688d018b]
[fv-az95-172:44339] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f48688af859]
[fv-az95-172:44339] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4868b37911]
[fv-az95-172:44339] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f4868b4338c]
[fv-az95-172:44339] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f4868b433f7]
[fv-az95-172:44339] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f4868b436a9]
[fv-az95-172:44339] [ 7] plumed(+0xf47d)[0x5640bf00347d]
[fv-az95-172:44339] [ 8] plumed(+0x14004)[0x5640bf008004]
[fv-az95-172:44339] [ 9] plumed(+0xf698)[0x5640bf003698]
[fv-az95-172:44339] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f48688b10b3]
[fv-az95-172:44339] [11] plumed(+0xf76e)[0x5640bf00376e]
[fv-az95-172:44339] *** End of error message ***
</pre>
{% endraw %}
