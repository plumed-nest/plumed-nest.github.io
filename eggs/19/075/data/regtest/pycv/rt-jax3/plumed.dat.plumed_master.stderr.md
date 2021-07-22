**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax3/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=r ATOMS=1,2,3 IMPORT=curvature FUNCTION=r
Maybe a missing space or a typo?
[fv-az95-172:59383] *** Process received signal ***
[fv-az95-172:59383] Signal: Aborted (6)
[fv-az95-172:59383] Signal code:  (-6)
[fv-az95-172:59383] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0c0ff09210]
[fv-az95-172:59383] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0c0ff0918b]
[fv-az95-172:59383] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0c0fee8859]
[fv-az95-172:59383] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0c10170911]
[fv-az95-172:59383] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0c1017c38c]
[fv-az95-172:59383] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0c1017c3f7]
[fv-az95-172:59383] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f0c1017c6fd]
[fv-az95-172:59383] [ 7] plumed_master(+0xf5b5)[0x5618e57295b5]
[fv-az95-172:59383] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0c0feea0b3]
[fv-az95-172:59383] [ 9] plumed_master(+0xf8be)[0x5618e57298be]
[fv-az95-172:59383] *** End of error message ***
</pre>
{% endraw %}
