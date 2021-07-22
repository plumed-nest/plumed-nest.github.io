**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w17-s4.402/plumed.dat   
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
[fv-az95-172:41804] *** Process received signal ***
[fv-az95-172:41804] Signal: Aborted (6)
[fv-az95-172:41804] Signal code:  (-6)
[fv-az95-172:41804] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f069f4d6210]
[fv-az95-172:41804] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f069f4d618b]
[fv-az95-172:41804] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f069f4b5859]
[fv-az95-172:41804] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f069f73d911]
[fv-az95-172:41804] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f069f74938c]
[fv-az95-172:41804] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f069f7493f7]
[fv-az95-172:41804] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f069f7496a9]
[fv-az95-172:41804] [ 7] plumed(+0xf47d)[0x55f6112a747d]
[fv-az95-172:41804] [ 8] plumed(+0x14004)[0x55f6112ac004]
[fv-az95-172:41804] [ 9] plumed(+0xf698)[0x55f6112a7698]
[fv-az95-172:41804] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f069f4b70b3]
[fv-az95-172:41804] [11] plumed(+0xf76e)[0x55f6112a776e]
[fv-az95-172:41804] *** End of error message ***
</pre>
{% endraw %}
