**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g7-w1-s7.9425/plumed.dat   
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
[fv-az95-172:41559] *** Process received signal ***
[fv-az95-172:41559] Signal: Aborted (6)
[fv-az95-172:41559] Signal code:  (-6)
[fv-az95-172:41559] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f15e51cb210]
[fv-az95-172:41559] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f15e51cb18b]
[fv-az95-172:41559] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f15e51aa859]
[fv-az95-172:41559] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f15e5432911]
[fv-az95-172:41559] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f15e543e38c]
[fv-az95-172:41559] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f15e543e3f7]
[fv-az95-172:41559] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f15e543e6a9]
[fv-az95-172:41559] [ 7] plumed(+0xf47d)[0x5640ade2247d]
[fv-az95-172:41559] [ 8] plumed(+0x14004)[0x5640ade27004]
[fv-az95-172:41559] [ 9] plumed(+0xf698)[0x5640ade22698]
[fv-az95-172:41559] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f15e51ac0b3]
[fv-az95-172:41559] [11] plumed(+0xf76e)[0x5640ade2276e]
[fv-az95-172:41559] *** End of error message ***
</pre>
{% endraw %}
