**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g2-w3-s10.004/plumed.dat   
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
[fv-az95-172:39575] *** Process received signal ***
[fv-az95-172:39575] Signal: Aborted (6)
[fv-az95-172:39575] Signal code:  (-6)
[fv-az95-172:39575] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f3a1219a210]
[fv-az95-172:39575] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f3a1219a18b]
[fv-az95-172:39575] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f3a12179859]
[fv-az95-172:39575] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f3a12401911]
[fv-az95-172:39575] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f3a1240d38c]
[fv-az95-172:39575] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f3a1240d3f7]
[fv-az95-172:39575] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f3a1240d6a9]
[fv-az95-172:39575] [ 7] plumed(+0xf47d)[0x562a3fd6747d]
[fv-az95-172:39575] [ 8] plumed(+0x14004)[0x562a3fd6c004]
[fv-az95-172:39575] [ 9] plumed(+0xf698)[0x562a3fd67698]
[fv-az95-172:39575] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f3a1217b0b3]
[fv-az95-172:39575] [11] plumed(+0xf76e)[0x562a3fd6776e]
[fv-az95-172:39575] *** End of error message ***
</pre>
{% endraw %}
