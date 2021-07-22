**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONFUNCTION LABEL=dAB2 ARG=dAB IMPORT=pythonfunction FUNCTION=square PERIODIC=NO
Maybe a missing space or a typo?
[fv-az95-172:59284] *** Process received signal ***
[fv-az95-172:59284] Signal: Aborted (6)
[fv-az95-172:59284] Signal code:  (-6)
[fv-az95-172:59284] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fcd2216a210]
[fv-az95-172:59284] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fcd2216a18b]
[fv-az95-172:59284] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fcd22149859]
[fv-az95-172:59284] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fcd223d1911]
[fv-az95-172:59284] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fcd223dd38c]
[fv-az95-172:59284] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fcd223dd3f7]
[fv-az95-172:59284] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fcd223dd6fd]
[fv-az95-172:59284] [ 7] plumed_master(+0xf5b5)[0x55771ebcc5b5]
[fv-az95-172:59284] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fcd2214b0b3]
[fv-az95-172:59284] [ 9] plumed_master(+0xf8be)[0x55771ebcc8be]
[fv-az95-172:59284] *** End of error message ***
</pre>
{% endraw %}
