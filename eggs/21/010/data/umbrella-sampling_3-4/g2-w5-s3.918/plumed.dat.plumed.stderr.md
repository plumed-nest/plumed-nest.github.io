**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_3-4/g2-w5-s3.918/plumed.dat   
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
[fv-az95-172:41194] *** Process received signal ***
[fv-az95-172:41194] Signal: Aborted (6)
[fv-az95-172:41194] Signal code:  (-6)
[fv-az95-172:41194] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc24dbd4210]
[fv-az95-172:41194] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc24dbd418b]
[fv-az95-172:41194] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc24dbb3859]
[fv-az95-172:41194] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc24de3b911]
[fv-az95-172:41194] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc24de4738c]
[fv-az95-172:41194] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc24de473f7]
[fv-az95-172:41194] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc24de476a9]
[fv-az95-172:41194] [ 7] plumed(+0xf47d)[0x55b7a2c4247d]
[fv-az95-172:41194] [ 8] plumed(+0x14004)[0x55b7a2c47004]
[fv-az95-172:41194] [ 9] plumed(+0xf698)[0x55b7a2c42698]
[fv-az95-172:41194] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc24dbb50b3]
[fv-az95-172:41194] [11] plumed(+0xf76e)[0x55b7a2c4276e]
[fv-az95-172:41194] *** End of error message ***
</pre>
{% endraw %}
