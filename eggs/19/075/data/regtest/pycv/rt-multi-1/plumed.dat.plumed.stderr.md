**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,3,4 IMPORT=distcv FUNCTION=cv COMPONENTS=d12,d13
Maybe a missing space or a typo?
[fv-az95-172:59399] *** Process received signal ***
[fv-az95-172:59399] Signal: Aborted (6)
[fv-az95-172:59399] Signal code:  (-6)
[fv-az95-172:59399] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe469d50210]
[fv-az95-172:59399] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe469d5018b]
[fv-az95-172:59399] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe469d2f859]
[fv-az95-172:59399] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe469fb7911]
[fv-az95-172:59399] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe469fc338c]
[fv-az95-172:59399] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe469fc33f7]
[fv-az95-172:59399] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fe469fc36a9]
[fv-az95-172:59399] [ 7] plumed(+0xf47d)[0x557cc1f0a47d]
[fv-az95-172:59399] [ 8] plumed(+0x14004)[0x557cc1f0f004]
[fv-az95-172:59399] [ 9] plumed(+0xf698)[0x557cc1f0a698]
[fv-az95-172:59399] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe469d310b3]
[fv-az95-172:59399] [11] plumed(+0xf76e)[0x557cc1f0a76e]
[fv-az95-172:59399] *** End of error message ***
</pre>
{% endraw %}
