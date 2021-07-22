**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w38-s7.588/plumed.dat   
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
[fv-az95-172:42373] *** Process received signal ***
[fv-az95-172:42373] Signal: Aborted (6)
[fv-az95-172:42373] Signal code:  (-6)
[fv-az95-172:42373] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f7bf94c4210]
[fv-az95-172:42373] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f7bf94c418b]
[fv-az95-172:42373] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7bf94a3859]
[fv-az95-172:42373] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f7bf972b911]
[fv-az95-172:42373] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f7bf973738c]
[fv-az95-172:42373] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f7bf97373f7]
[fv-az95-172:42373] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f7bf97376a9]
[fv-az95-172:42373] [ 7] plumed(+0xf47d)[0x5559ead5147d]
[fv-az95-172:42373] [ 8] plumed(+0x14004)[0x5559ead56004]
[fv-az95-172:42373] [ 9] plumed(+0xf698)[0x5559ead51698]
[fv-az95-172:42373] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f7bf94a50b3]
[fv-az95-172:42373] [11] plumed(+0xf76e)[0x5559ead5176e]
[fv-az95-172:42373] *** End of error message ***
</pre>
{% endraw %}
