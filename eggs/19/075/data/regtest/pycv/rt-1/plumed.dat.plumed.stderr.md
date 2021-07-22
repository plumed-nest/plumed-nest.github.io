**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4 IMPORT=pycv FUNCTION=cv1
Maybe a missing space or a typo?
[fv-az95-172:59203] *** Process received signal ***
[fv-az95-172:59203] Signal: Aborted (6)
[fv-az95-172:59203] Signal code:  (-6)
[fv-az95-172:59203] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f7c893f4210]
[fv-az95-172:59203] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f7c893f418b]
[fv-az95-172:59203] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7c893d3859]
[fv-az95-172:59203] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f7c8965b911]
[fv-az95-172:59203] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f7c8966738c]
[fv-az95-172:59203] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f7c896673f7]
[fv-az95-172:59203] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f7c896676a9]
[fv-az95-172:59203] [ 7] plumed(+0xf47d)[0x56524a22b47d]
[fv-az95-172:59203] [ 8] plumed(+0x14004)[0x56524a230004]
[fv-az95-172:59203] [ 9] plumed(+0xf698)[0x56524a22b698]
[fv-az95-172:59203] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f7c893d50b3]
[fv-az95-172:59203] [11] plumed(+0xf76e)[0x56524a22b76e]
[fv-az95-172:59203] *** End of error message ***
</pre>
{% endraw %}
