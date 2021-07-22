**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  4_silicon/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: REFCV SPECIES=1-216 SIGMA=0.04 LATTICE_CONSTANTS=0.5431 CRYSTAL_STRUCTURE=DIAMOND LABEL=refcv MORE_THAN=RATIONAL R_0=0.5 NN=12 MM=24 MEAN
Maybe a missing space or a typo?
[fv-az95-172:65015] *** Process received signal ***
[fv-az95-172:65015] Signal: Aborted (6)
[fv-az95-172:65015] Signal code:  (-6)
[fv-az95-172:65015] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fdddae8a210]
[fv-az95-172:65015] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fdddae8a18b]
[fv-az95-172:65015] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fdddae69859]
[fv-az95-172:65015] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fdddb0f1911]
[fv-az95-172:65015] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fdddb0fd38c]
[fv-az95-172:65015] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fdddb0fd3f7]
[fv-az95-172:65015] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fdddb0fd6a9]
[fv-az95-172:65015] [ 7] plumed(+0xf47d)[0x56018d77147d]
[fv-az95-172:65015] [ 8] plumed(+0x14004)[0x56018d776004]
[fv-az95-172:65015] [ 9] plumed(+0xf698)[0x56018d771698]
[fv-az95-172:65015] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fdddae6b0b3]
[fv-az95-172:65015] [11] plumed(+0xf76e)[0x56018d77176e]
[fv-az95-172:65015] *** End of error message ***
</pre>
{% endraw %}
