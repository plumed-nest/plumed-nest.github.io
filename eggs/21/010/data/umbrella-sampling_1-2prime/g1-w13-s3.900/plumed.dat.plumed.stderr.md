**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w13-s3.900/plumed.dat   
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
[fv-az95-172:37487] *** Process received signal ***
[fv-az95-172:37487] Signal: Aborted (6)
[fv-az95-172:37487] Signal code:  (-6)
[fv-az95-172:37487] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f7591398210]
[fv-az95-172:37487] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f759139818b]
[fv-az95-172:37487] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7591377859]
[fv-az95-172:37487] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f75915ff911]
[fv-az95-172:37487] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f759160b38c]
[fv-az95-172:37487] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f759160b3f7]
[fv-az95-172:37487] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f759160b6a9]
[fv-az95-172:37487] [ 7] plumed(+0xf47d)[0x55dd33ae747d]
[fv-az95-172:37487] [ 8] plumed(+0x14004)[0x55dd33aec004]
[fv-az95-172:37487] [ 9] plumed(+0xf698)[0x55dd33ae7698]
[fv-az95-172:37487] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f75913790b3]
[fv-az95-172:37487] [11] plumed(+0xf76e)[0x55dd33ae776e]
[fv-az95-172:37487] *** End of error message ***
</pre>
{% endraw %}
