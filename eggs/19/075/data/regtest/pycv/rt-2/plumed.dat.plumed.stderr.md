**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4 IMPORT=distcv FUNCTION=cv
Maybe a missing space or a typo?
[fv-az95-172:59228] *** Process received signal ***
[fv-az95-172:59228] Signal: Aborted (6)
[fv-az95-172:59228] Signal code:  (-6)
[fv-az95-172:59228] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0ec80cc210]
[fv-az95-172:59228] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0ec80cc18b]
[fv-az95-172:59228] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0ec80ab859]
[fv-az95-172:59228] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0ec8333911]
[fv-az95-172:59228] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0ec833f38c]
[fv-az95-172:59228] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0ec833f3f7]
[fv-az95-172:59228] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0ec833f6a9]
[fv-az95-172:59228] [ 7] plumed(+0xf47d)[0x563fb63f347d]
[fv-az95-172:59228] [ 8] plumed(+0x14004)[0x563fb63f8004]
[fv-az95-172:59228] [ 9] plumed(+0xf698)[0x563fb63f3698]
[fv-az95-172:59228] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0ec80ad0b3]
[fv-az95-172:59228] [11] plumed(+0xf76e)[0x563fb63f376e]
[fv-az95-172:59228] *** End of error message ***
</pre>
{% endraw %}
