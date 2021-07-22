**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g201-w2-s6.190/plumed.dat   
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
[fv-az95-172:41340] *** Process received signal ***
[fv-az95-172:41340] Signal: Aborted (6)
[fv-az95-172:41340] Signal code:  (-6)
[fv-az95-172:41340] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe5b0ced210]
[fv-az95-172:41340] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe5b0ced18b]
[fv-az95-172:41340] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe5b0ccc859]
[fv-az95-172:41340] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe5b0f54911]
[fv-az95-172:41340] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe5b0f6038c]
[fv-az95-172:41340] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe5b0f603f7]
[fv-az95-172:41340] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fe5b0f606a9]
[fv-az95-172:41340] [ 7] plumed(+0xf47d)[0x560aaa6d447d]
[fv-az95-172:41340] [ 8] plumed(+0x14004)[0x560aaa6d9004]
[fv-az95-172:41340] [ 9] plumed(+0xf698)[0x560aaa6d4698]
[fv-az95-172:41340] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe5b0cce0b3]
[fv-az95-172:41340] [11] plumed(+0xf76e)[0x560aaa6d476e]
[fv-az95-172:41340] *** End of error message ***
</pre>
{% endraw %}
