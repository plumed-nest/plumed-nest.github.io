**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2prime-2/g1-w5-s5.963/plumed.dat   
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
[fv-az95-172:40116] *** Process received signal ***
[fv-az95-172:40116] Signal: Aborted (6)
[fv-az95-172:40116] Signal code:  (-6)
[fv-az95-172:40116] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fbc22500210]
[fv-az95-172:40116] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fbc2250018b]
[fv-az95-172:40116] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fbc224df859]
[fv-az95-172:40116] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fbc22767911]
[fv-az95-172:40116] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fbc2277338c]
[fv-az95-172:40116] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fbc227733f7]
[fv-az95-172:40116] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fbc227736a9]
[fv-az95-172:40116] [ 7] plumed(+0xf47d)[0x563d7ba9747d]
[fv-az95-172:40116] [ 8] plumed(+0x14004)[0x563d7ba9c004]
[fv-az95-172:40116] [ 9] plumed(+0xf698)[0x563d7ba97698]
[fv-az95-172:40116] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fbc224e10b3]
[fv-az95-172:40116] [11] plumed(+0xf76e)[0x563d7ba9776e]
[fv-az95-172:40116] *** End of error message ***
</pre>
{% endraw %}
