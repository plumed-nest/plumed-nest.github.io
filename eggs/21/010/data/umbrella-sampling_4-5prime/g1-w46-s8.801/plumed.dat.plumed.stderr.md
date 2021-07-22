**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g1-w46-s8.801/plumed.dat   
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
[fv-az95-172:42594] *** Process received signal ***
[fv-az95-172:42594] Signal: Aborted (6)
[fv-az95-172:42594] Signal code:  (-6)
[fv-az95-172:42594] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe5e624a210]
[fv-az95-172:42594] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe5e624a18b]
[fv-az95-172:42594] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe5e6229859]
[fv-az95-172:42594] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe5e64b1911]
[fv-az95-172:42594] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe5e64bd38c]
[fv-az95-172:42594] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe5e64bd3f7]
[fv-az95-172:42594] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fe5e64bd6a9]
[fv-az95-172:42594] [ 7] plumed(+0xf47d)[0x556310b0547d]
[fv-az95-172:42594] [ 8] plumed(+0x14004)[0x556310b0a004]
[fv-az95-172:42594] [ 9] plumed(+0xf698)[0x556310b05698]
[fv-az95-172:42594] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe5e622b0b3]
[fv-az95-172:42594] [11] plumed(+0xf76e)[0x556310b0576e]
[fv-az95-172:42594] *** End of error message ***
</pre>
{% endraw %}
