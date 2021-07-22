**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_4-5prime/g2-w3-s5.88125/plumed.dat   
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
[fv-az95-172:43136] *** Process received signal ***
[fv-az95-172:43136] Signal: Aborted (6)
[fv-az95-172:43136] Signal code:  (-6)
[fv-az95-172:43136] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc9d246c210]
[fv-az95-172:43136] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc9d246c18b]
[fv-az95-172:43136] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc9d244b859]
[fv-az95-172:43136] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc9d26d3911]
[fv-az95-172:43136] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc9d26df38c]
[fv-az95-172:43136] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc9d26df3f7]
[fv-az95-172:43136] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc9d26df6a9]
[fv-az95-172:43136] [ 7] plumed(+0xf47d)[0x55b26326f47d]
[fv-az95-172:43136] [ 8] plumed(+0x14004)[0x55b263274004]
[fv-az95-172:43136] [ 9] plumed(+0xf698)[0x55b26326f698]
[fv-az95-172:43136] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc9d244d0b3]
[fv-az95-172:43136] [11] plumed(+0xf76e)[0x55b26326f76e]
[fv-az95-172:43136] *** End of error message ***
</pre>
{% endraw %}
