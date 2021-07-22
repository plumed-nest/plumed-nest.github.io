**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w21-s8.072/plumed.dat   
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
[fv-az95-172:40997] *** Process received signal ***
[fv-az95-172:40997] Signal: Aborted (6)
[fv-az95-172:40997] Signal code:  (-6)
[fv-az95-172:40997] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4956488210]
[fv-az95-172:40997] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f495648818b]
[fv-az95-172:40997] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4956467859]
[fv-az95-172:40997] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f49566ef911]
[fv-az95-172:40997] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f49566fb38c]
[fv-az95-172:40997] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f49566fb3f7]
[fv-az95-172:40997] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f49566fb6a9]
[fv-az95-172:40997] [ 7] plumed(+0xf47d)[0x55c57f19347d]
[fv-az95-172:40997] [ 8] plumed(+0x14004)[0x55c57f198004]
[fv-az95-172:40997] [ 9] plumed(+0xf698)[0x55c57f193698]
[fv-az95-172:40997] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f49564690b3]
[fv-az95-172:40997] [11] plumed(+0xf76e)[0x55c57f19376e]
[fv-az95-172:40997] *** End of error message ***
</pre>
{% endraw %}
