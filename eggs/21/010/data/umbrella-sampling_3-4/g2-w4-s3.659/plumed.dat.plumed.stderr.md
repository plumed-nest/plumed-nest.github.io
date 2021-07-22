**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w4-s3.659/plumed.dat   
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
[fv-az95-172:41170] *** Process received signal ***
[fv-az95-172:41170] Signal: Aborted (6)
[fv-az95-172:41170] Signal code:  (-6)
[fv-az95-172:41170] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f234bf87210]
[fv-az95-172:41170] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f234bf8718b]
[fv-az95-172:41170] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f234bf66859]
[fv-az95-172:41170] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f234c1ee911]
[fv-az95-172:41170] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f234c1fa38c]
[fv-az95-172:41170] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f234c1fa3f7]
[fv-az95-172:41170] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f234c1fa6a9]
[fv-az95-172:41170] [ 7] plumed(+0xf47d)[0x55c03f7bd47d]
[fv-az95-172:41170] [ 8] plumed(+0x14004)[0x55c03f7c2004]
[fv-az95-172:41170] [ 9] plumed(+0xf698)[0x55c03f7bd698]
[fv-az95-172:41170] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f234bf680b3]
[fv-az95-172:41170] [11] plumed(+0xf76e)[0x55c03f7bd76e]
[fv-az95-172:41170] *** End of error message ***
</pre>
{% endraw %}
