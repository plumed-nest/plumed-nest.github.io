**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONFUNCTION LABEL=cc1 ARG=t1,t2,t3 IMPORT=pythonfunction FUNCTION=cc1 PERIODIC=NO
Maybe a missing space or a typo?
[fv-az95-172:59301] *** Process received signal ***
[fv-az95-172:59301] Signal: Aborted (6)
[fv-az95-172:59301] Signal code:  (-6)
[fv-az95-172:59301] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0289f4d210]
[fv-az95-172:59301] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0289f4d18b]
[fv-az95-172:59301] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0289f2c859]
[fv-az95-172:59301] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f028a1b4911]
[fv-az95-172:59301] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f028a1c038c]
[fv-az95-172:59301] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f028a1c03f7]
[fv-az95-172:59301] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f028a1c06a9]
[fv-az95-172:59301] [ 7] plumed(+0xf47d)[0x56016e40847d]
[fv-az95-172:59301] [ 8] plumed(+0x14004)[0x56016e40d004]
[fv-az95-172:59301] [ 9] plumed(+0xf698)[0x56016e408698]
[fv-az95-172:59301] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0289f2e0b3]
[fv-az95-172:59301] [11] plumed(+0xf76e)[0x56016e40876e]
[fv-az95-172:59301] *** End of error message ***
</pre>
{% endraw %}
