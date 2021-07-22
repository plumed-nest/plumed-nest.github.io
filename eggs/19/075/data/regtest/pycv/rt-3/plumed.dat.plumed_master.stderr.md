**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4 IMPORT=distcv FUNCTION=cv
Maybe a missing space or a typo?
[fv-az95-172:59260] *** Process received signal ***
[fv-az95-172:59260] Signal: Aborted (6)
[fv-az95-172:59260] Signal code:  (-6)
[fv-az95-172:59260] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fe4794f6210]
[fv-az95-172:59260] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fe4794f618b]
[fv-az95-172:59260] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fe4794d5859]
[fv-az95-172:59260] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fe47975d911]
[fv-az95-172:59260] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fe47976938c]
[fv-az95-172:59260] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fe4797693f7]
[fv-az95-172:59260] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fe4797696fd]
[fv-az95-172:59260] [ 7] plumed_master(+0xf5b5)[0x56060ded45b5]
[fv-az95-172:59260] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fe4794d70b3]
[fv-az95-172:59260] [ 9] plumed_master(+0xf8be)[0x56060ded48be]
[fv-az95-172:59260] *** End of error message ***
</pre>
{% endraw %}
