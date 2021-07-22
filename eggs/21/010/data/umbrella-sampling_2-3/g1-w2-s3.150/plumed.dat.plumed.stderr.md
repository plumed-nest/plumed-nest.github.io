**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w2-s3.150/plumed.dat   
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
[fv-az95-172:39084] *** Process received signal ***
[fv-az95-172:39084] Signal: Aborted (6)
[fv-az95-172:39084] Signal code:  (-6)
[fv-az95-172:39084] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4e96597210]
[fv-az95-172:39084] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f4e9659718b]
[fv-az95-172:39084] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4e96576859]
[fv-az95-172:39084] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4e967fe911]
[fv-az95-172:39084] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f4e9680a38c]
[fv-az95-172:39084] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f4e9680a3f7]
[fv-az95-172:39084] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f4e9680a6a9]
[fv-az95-172:39084] [ 7] plumed(+0xf47d)[0x55e4d7ad447d]
[fv-az95-172:39084] [ 8] plumed(+0x14004)[0x55e4d7ad9004]
[fv-az95-172:39084] [ 9] plumed(+0xf698)[0x55e4d7ad4698]
[fv-az95-172:39084] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f4e965780b3]
[fv-az95-172:39084] [11] plumed(+0xf76e)[0x55e4d7ad476e]
[fv-az95-172:39084] *** End of error message ***
</pre>
{% endraw %}
