**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-2-jax/plumed.dat   
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
[fv-az95-172:59424] *** Process received signal ***
[fv-az95-172:59424] Signal: Aborted (6)
[fv-az95-172:59424] Signal code:  (-6)
[fv-az95-172:59424] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fdf0c98c210]
[fv-az95-172:59424] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fdf0c98c18b]
[fv-az95-172:59424] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fdf0c96b859]
[fv-az95-172:59424] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fdf0cbf3911]
[fv-az95-172:59424] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fdf0cbff38c]
[fv-az95-172:59424] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fdf0cbff3f7]
[fv-az95-172:59424] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fdf0cbff6a9]
[fv-az95-172:59424] [ 7] plumed(+0xf47d)[0x5602f4ca947d]
[fv-az95-172:59424] [ 8] plumed(+0x14004)[0x5602f4cae004]
[fv-az95-172:59424] [ 9] plumed(+0xf698)[0x5602f4ca9698]
[fv-az95-172:59424] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fdf0c96d0b3]
[fv-az95-172:59424] [11] plumed(+0xf76e)[0x5602f4ca976e]
[fv-az95-172:59424] *** End of error message ***
</pre>
{% endraw %}
