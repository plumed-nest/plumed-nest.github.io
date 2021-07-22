**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_2-3/g1-w18-s8.508/plumed.dat   
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
[fv-az95-172:39011] *** Process received signal ***
[fv-az95-172:39011] Signal: Aborted (6)
[fv-az95-172:39011] Signal code:  (-6)
[fv-az95-172:39011] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f232746e210]
[fv-az95-172:39011] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f232746e18b]
[fv-az95-172:39011] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f232744d859]
[fv-az95-172:39011] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f23276d5911]
[fv-az95-172:39011] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f23276e138c]
[fv-az95-172:39011] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f23276e13f7]
[fv-az95-172:39011] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f23276e16a9]
[fv-az95-172:39011] [ 7] plumed(+0xf47d)[0x56396728a47d]
[fv-az95-172:39011] [ 8] plumed(+0x14004)[0x56396728f004]
[fv-az95-172:39011] [ 9] plumed(+0xf698)[0x56396728a698]
[fv-az95-172:39011] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f232744f0b3]
[fv-az95-172:39011] [11] plumed(+0xf76e)[0x56396728a76e]
[fv-az95-172:39011] *** End of error message ***
</pre>
{% endraw %}
