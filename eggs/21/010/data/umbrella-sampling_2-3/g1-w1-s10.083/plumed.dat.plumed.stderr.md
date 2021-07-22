**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w1-s10.083/plumed.dat   
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
[fv-az95-172:38766] *** Process received signal ***
[fv-az95-172:38766] Signal: Aborted (6)
[fv-az95-172:38766] Signal code:  (-6)
[fv-az95-172:38766] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f38c79d0210]
[fv-az95-172:38766] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f38c79d018b]
[fv-az95-172:38766] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f38c79af859]
[fv-az95-172:38766] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f38c7c37911]
[fv-az95-172:38766] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f38c7c4338c]
[fv-az95-172:38766] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f38c7c433f7]
[fv-az95-172:38766] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f38c7c436a9]
[fv-az95-172:38766] [ 7] plumed(+0xf47d)[0x562fb059c47d]
[fv-az95-172:38766] [ 8] plumed(+0x14004)[0x562fb05a1004]
[fv-az95-172:38766] [ 9] plumed(+0xf698)[0x562fb059c698]
[fv-az95-172:38766] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f38c79b10b3]
[fv-az95-172:38766] [11] plumed(+0xf76e)[0x562fb059c76e]
[fv-az95-172:38766] *** End of error message ***
</pre>
{% endraw %}
