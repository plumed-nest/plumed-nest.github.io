**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w2-s5.588/plumed.dat   
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
[fv-az95-172:39920] *** Process received signal ***
[fv-az95-172:39920] Signal: Aborted (6)
[fv-az95-172:39920] Signal code:  (-6)
[fv-az95-172:39920] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fdf0ac88210]
[fv-az95-172:39920] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fdf0ac8818b]
[fv-az95-172:39920] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fdf0ac67859]
[fv-az95-172:39920] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fdf0aeef911]
[fv-az95-172:39920] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fdf0aefb38c]
[fv-az95-172:39920] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fdf0aefb3f7]
[fv-az95-172:39920] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fdf0aefb6a9]
[fv-az95-172:39920] [ 7] plumed(+0xf47d)[0x5557fa2f847d]
[fv-az95-172:39920] [ 8] plumed(+0x14004)[0x5557fa2fd004]
[fv-az95-172:39920] [ 9] plumed(+0xf698)[0x5557fa2f8698]
[fv-az95-172:39920] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fdf0ac690b3]
[fv-az95-172:39920] [11] plumed(+0xf76e)[0x5557fa2f876e]
[fv-az95-172:39920] *** End of error message ***
</pre>
{% endraw %}
