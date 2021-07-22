**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: HBOND_COORD SPECIES=2665-10353:4 HYDROGENS=2666-10354:4,2667-10355:4 RCUTOO=0.324 RCUTOH=0.25 ACUT=0.20pi LABEL=hb
Maybe a missing space or a typo?
[fv-az95-172:69195] *** Process received signal ***
[fv-az95-172:69195] Signal: Aborted (6)
[fv-az95-172:69195] Signal code:  (-6)
[fv-az95-172:69195] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fa94b246210]
[fv-az95-172:69195] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fa94b24618b]
[fv-az95-172:69195] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fa94b225859]
[fv-az95-172:69195] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fa94b4ad911]
[fv-az95-172:69195] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fa94b4b938c]
[fv-az95-172:69195] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fa94b4b93f7]
[fv-az95-172:69195] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fa94b4b96fd]
[fv-az95-172:69195] [ 7] plumed_master(+0xf5b5)[0x563b805525b5]
[fv-az95-172:69195] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fa94b2270b3]
[fv-az95-172:69195] [ 9] plumed_master(+0xf8be)[0x563b805528be]
[fv-az95-172:69195] *** End of error message ***
</pre>
{% endraw %}
