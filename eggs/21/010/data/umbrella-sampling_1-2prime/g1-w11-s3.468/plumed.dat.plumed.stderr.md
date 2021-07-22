**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w11-s3.468/plumed.dat   
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
[fv-az95-172:37437] *** Process received signal ***
[fv-az95-172:37437] Signal: Aborted (6)
[fv-az95-172:37437] Signal code:  (-6)
[fv-az95-172:37437] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fd654244210]
[fv-az95-172:37437] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fd65424418b]
[fv-az95-172:37437] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fd654223859]
[fv-az95-172:37437] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fd6544ab911]
[fv-az95-172:37437] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fd6544b738c]
[fv-az95-172:37437] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fd6544b73f7]
[fv-az95-172:37437] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fd6544b76a9]
[fv-az95-172:37437] [ 7] plumed(+0xf47d)[0x55de665c047d]
[fv-az95-172:37437] [ 8] plumed(+0x14004)[0x55de665c5004]
[fv-az95-172:37437] [ 9] plumed(+0xf698)[0x55de665c0698]
[fv-az95-172:37437] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fd6542250b3]
[fv-az95-172:37437] [11] plumed(+0xf76e)[0x55de665c076e]
[fv-az95-172:37437] *** End of error message ***
</pre>
{% endraw %}
