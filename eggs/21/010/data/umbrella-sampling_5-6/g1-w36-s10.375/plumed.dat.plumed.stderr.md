**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_5-6/g1-w36-s10.375/plumed.dat   
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
[fv-az95-172:43923] *** Process received signal ***
[fv-az95-172:43923] Signal: Aborted (6)
[fv-az95-172:43923] Signal code:  (-6)
[fv-az95-172:43923] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6301caf210]
[fv-az95-172:43923] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f6301caf18b]
[fv-az95-172:43923] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6301c8e859]
[fv-az95-172:43923] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6301f16911]
[fv-az95-172:43923] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6301f2238c]
[fv-az95-172:43923] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6301f223f7]
[fv-az95-172:43923] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f6301f226a9]
[fv-az95-172:43923] [ 7] plumed(+0xf47d)[0x55c745b0447d]
[fv-az95-172:43923] [ 8] plumed(+0x14004)[0x55c745b09004]
[fv-az95-172:43923] [ 9] plumed(+0xf698)[0x55c745b04698]
[fv-az95-172:43923] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f6301c900b3]
[fv-az95-172:43923] [11] plumed(+0xf76e)[0x55c745b0476e]
[fv-az95-172:43923] *** End of error message ***
</pre>
{% endraw %}
