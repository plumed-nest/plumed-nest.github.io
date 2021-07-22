**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONFUNCTION LABEL=dAB2 ARG=dAB IMPORT=pythonfunction FUNCTION=square PERIODIC=NO
Maybe a missing space or a typo?
[fv-az95-172:59276] *** Process received signal ***
[fv-az95-172:59276] Signal: Aborted (6)
[fv-az95-172:59276] Signal code:  (-6)
[fv-az95-172:59276] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fca76567210]
[fv-az95-172:59276] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fca7656718b]
[fv-az95-172:59276] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fca76546859]
[fv-az95-172:59276] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fca767ce911]
[fv-az95-172:59276] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fca767da38c]
[fv-az95-172:59276] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fca767da3f7]
[fv-az95-172:59276] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fca767da6a9]
[fv-az95-172:59276] [ 7] plumed(+0xf47d)[0x55de1641247d]
[fv-az95-172:59276] [ 8] plumed(+0x14004)[0x55de16417004]
[fv-az95-172:59276] [ 9] plumed(+0xf698)[0x55de16412698]
[fv-az95-172:59276] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fca765480b3]
[fv-az95-172:59276] [11] plumed(+0xf76e)[0x55de1641276e]
[fv-az95-172:59276] *** End of error message ***
</pre>
{% endraw %}
