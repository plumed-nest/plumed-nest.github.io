**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w27-s6.924/plumed.dat   
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
[fv-az95-172:37854] *** Process received signal ***
[fv-az95-172:37854] Signal: Aborted (6)
[fv-az95-172:37854] Signal code:  (-6)
[fv-az95-172:37854] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f284300d210]
[fv-az95-172:37854] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f284300d18b]
[fv-az95-172:37854] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2842fec859]
[fv-az95-172:37854] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2843274911]
[fv-az95-172:37854] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f284328038c]
[fv-az95-172:37854] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f28432803f7]
[fv-az95-172:37854] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f28432806a9]
[fv-az95-172:37854] [ 7] plumed(+0xf47d)[0x561fe23e947d]
[fv-az95-172:37854] [ 8] plumed(+0x14004)[0x561fe23ee004]
[fv-az95-172:37854] [ 9] plumed(+0xf698)[0x561fe23e9698]
[fv-az95-172:37854] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2842fee0b3]
[fv-az95-172:37854] [11] plumed(+0xf76e)[0x561fe23e976e]
[fv-az95-172:37854] *** End of error message ***
</pre>
{% endraw %}
