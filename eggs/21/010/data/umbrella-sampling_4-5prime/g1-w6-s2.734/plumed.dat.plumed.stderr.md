**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w6-s2.734/plumed.dat   
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
[fv-az95-172:42964] *** Process received signal ***
[fv-az95-172:42964] Signal: Aborted (6)
[fv-az95-172:42964] Signal code:  (-6)
[fv-az95-172:42964] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2cdc3f0210]
[fv-az95-172:42964] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2cdc3f018b]
[fv-az95-172:42964] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2cdc3cf859]
[fv-az95-172:42964] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2cdc657911]
[fv-az95-172:42964] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2cdc66338c]
[fv-az95-172:42964] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2cdc6633f7]
[fv-az95-172:42964] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f2cdc6636a9]
[fv-az95-172:42964] [ 7] plumed(+0xf47d)[0x563a8d40647d]
[fv-az95-172:42964] [ 8] plumed(+0x14004)[0x563a8d40b004]
[fv-az95-172:42964] [ 9] plumed(+0xf698)[0x563a8d406698]
[fv-az95-172:42964] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2cdc3d10b3]
[fv-az95-172:42964] [11] plumed(+0xf76e)[0x563a8d40676e]
[fv-az95-172:42964] *** End of error message ***
</pre>
{% endraw %}
