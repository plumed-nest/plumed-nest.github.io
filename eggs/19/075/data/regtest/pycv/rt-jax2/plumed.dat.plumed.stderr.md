**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4,3 IMPORT=jaxcv FUNCTION=cv1
Maybe a missing space or a typo?
[fv-az95-172:59351] *** Process received signal ***
[fv-az95-172:59351] Signal: Aborted (6)
[fv-az95-172:59351] Signal code:  (-6)
[fv-az95-172:59351] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f7e37032210]
[fv-az95-172:59351] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f7e3703218b]
[fv-az95-172:59351] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f7e37011859]
[fv-az95-172:59351] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f7e37299911]
[fv-az95-172:59351] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f7e372a538c]
[fv-az95-172:59351] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f7e372a53f7]
[fv-az95-172:59351] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f7e372a56a9]
[fv-az95-172:59351] [ 7] plumed(+0xf47d)[0x55698a18d47d]
[fv-az95-172:59351] [ 8] plumed(+0x14004)[0x55698a192004]
[fv-az95-172:59351] [ 9] plumed(+0xf698)[0x55698a18d698]
[fv-az95-172:59351] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f7e370130b3]
[fv-az95-172:59351] [11] plumed(+0xf76e)[0x55698a18d76e]
[fv-az95-172:59351] *** End of error message ***
</pre>
{% endraw %}
