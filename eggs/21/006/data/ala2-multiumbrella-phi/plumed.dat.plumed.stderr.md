**Project ID:** [plumID:21.006]({{ '/' | absolute_url }}eggs/21/006/)  
Stderr for source:  ala2-multiumbrella-phi/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ECV_UMBRELLAS_LINE LABEL=ecv ARG=phi MIN_CV=-pi MAX_CV=pi SIGMA=0.15 BARRIER=50
Maybe a missing space or a typo?
[fv-az95-172:46441] *** Process received signal ***
[fv-az95-172:46441] Signal: Aborted (6)
[fv-az95-172:46441] Signal code:  (-6)
[fv-az95-172:46441] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f0f0d1c0210]
[fv-az95-172:46441] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f0f0d1c018b]
[fv-az95-172:46441] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f0f0d19f859]
[fv-az95-172:46441] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f0f0d427911]
[fv-az95-172:46441] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f0f0d43338c]
[fv-az95-172:46441] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f0f0d4333f7]
[fv-az95-172:46441] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f0f0d4336a9]
[fv-az95-172:46441] [ 7] plumed(+0xf47d)[0x56521c40047d]
[fv-az95-172:46441] [ 8] plumed(+0x14004)[0x56521c405004]
[fv-az95-172:46441] [ 9] plumed(+0xf698)[0x56521c400698]
[fv-az95-172:46441] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f0f0d1a10b3]
[fv-az95-172:46441] [11] plumed(+0xf76e)[0x56521c40076e]
[fv-az95-172:46441] *** End of error message ***
</pre>
{% endraw %}
