**Project ID:** [plumID:20.022]({{ '/' | absolute_url }}eggs/20/022/)  
Stderr for source:  water/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_LINEAR LABEL=ecv ARG=DeltaU TEMP=443
Maybe a missing space or a typo?
[fv-az95-172:51491] *** Process received signal ***
[fv-az95-172:51491] Signal: Aborted (6)
[fv-az95-172:51491] Signal code:  (-6)
[fv-az95-172:51491] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f4137c34210]
[fv-az95-172:51491] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f4137c3418b]
[fv-az95-172:51491] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f4137c13859]
[fv-az95-172:51491] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4137e9b911]
[fv-az95-172:51491] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f4137ea738c]
[fv-az95-172:51491] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f4137ea73f7]
[fv-az95-172:51491] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f4137ea76a9]
[fv-az95-172:51491] [ 7] plumed(+0xf47d)[0x55ca41f5147d]
[fv-az95-172:51491] [ 8] plumed(+0x14004)[0x55ca41f56004]
[fv-az95-172:51491] [ 9] plumed(+0xf698)[0x55ca41f51698]
[fv-az95-172:51491] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f4137c150b3]
[fv-az95-172:51491] [11] plumed(+0xf76e)[0x55ca41f5176e]
[fv-az95-172:51491] *** End of error message ***
</pre>
{% endraw %}
