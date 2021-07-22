**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4 IMPORT=jaxcv FUNCTION=cv1
Maybe a missing space or a typo?
[fv-az95-172:59327] *** Process received signal ***
[fv-az95-172:59327] Signal: Aborted (6)
[fv-az95-172:59327] Signal code:  (-6)
[fv-az95-172:59327] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f5d51376210]
[fv-az95-172:59327] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f5d5137618b]
[fv-az95-172:59327] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f5d51355859]
[fv-az95-172:59327] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f5d515dd911]
[fv-az95-172:59327] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f5d515e938c]
[fv-az95-172:59327] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f5d515e93f7]
[fv-az95-172:59327] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f5d515e96a9]
[fv-az95-172:59327] [ 7] plumed(+0xf47d)[0x55884340947d]
[fv-az95-172:59327] [ 8] plumed(+0x14004)[0x55884340e004]
[fv-az95-172:59327] [ 9] plumed(+0xf698)[0x558843409698]
[fv-az95-172:59327] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f5d513570b3]
[fv-az95-172:59327] [11] plumed(+0xf76e)[0x55884340976e]
[fv-az95-172:59327] *** End of error message ***
</pre>
{% endraw %}
