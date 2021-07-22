**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w1-s1.625/plumed.dat   
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
[fv-az95-172:43208] *** Process received signal ***
[fv-az95-172:43208] Signal: Aborted (6)
[fv-az95-172:43208] Signal code:  (-6)
[fv-az95-172:43208] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fb3b9512210]
[fv-az95-172:43208] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fb3b951218b]
[fv-az95-172:43208] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fb3b94f1859]
[fv-az95-172:43208] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fb3b9779911]
[fv-az95-172:43208] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fb3b978538c]
[fv-az95-172:43208] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fb3b97853f7]
[fv-az95-172:43208] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fb3b97856a9]
[fv-az95-172:43208] [ 7] plumed(+0xf47d)[0x558dbc22847d]
[fv-az95-172:43208] [ 8] plumed(+0x14004)[0x558dbc22d004]
[fv-az95-172:43208] [ 9] plumed(+0xf698)[0x558dbc228698]
[fv-az95-172:43208] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fb3b94f30b3]
[fv-az95-172:43208] [11] plumed(+0xf76e)[0x558dbc22876e]
[fv-az95-172:43208] *** End of error message ***
</pre>
{% endraw %}
