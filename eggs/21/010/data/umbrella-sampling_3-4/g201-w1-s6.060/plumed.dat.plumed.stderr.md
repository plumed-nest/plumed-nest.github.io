**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g201-w1-s6.060/plumed.dat   
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
[fv-az95-172:41316] *** Process received signal ***
[fv-az95-172:41316] Signal: Aborted (6)
[fv-az95-172:41316] Signal code:  (-6)
[fv-az95-172:41316] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fecc034f210]
[fv-az95-172:41316] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fecc034f18b]
[fv-az95-172:41316] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fecc032e859]
[fv-az95-172:41316] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fecc05b6911]
[fv-az95-172:41316] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fecc05c238c]
[fv-az95-172:41316] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fecc05c23f7]
[fv-az95-172:41316] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fecc05c26a9]
[fv-az95-172:41316] [ 7] plumed(+0xf47d)[0x55b9fd87447d]
[fv-az95-172:41316] [ 8] plumed(+0x14004)[0x55b9fd879004]
[fv-az95-172:41316] [ 9] plumed(+0xf698)[0x55b9fd874698]
[fv-az95-172:41316] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fecc03300b3]
[fv-az95-172:41316] [11] plumed(+0xf76e)[0x55b9fd87476e]
[fv-az95-172:41316] *** End of error message ***
</pre>
{% endraw %}
