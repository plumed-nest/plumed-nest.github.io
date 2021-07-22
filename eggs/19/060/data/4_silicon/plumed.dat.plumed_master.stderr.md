**Project ID:** [plumID:19.060]({{ '/' | absolute_url }}eggs/19/060/)  
Stderr for source:  4_silicon/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: REFCV SPECIES=1-216 SIGMA=0.04 LATTICE_CONSTANTS=0.5431 CRYSTAL_STRUCTURE=DIAMOND LABEL=refcv MORE_THAN=RATIONAL R_0=0.5 NN=12 MM=24 MEAN
Maybe a missing space or a typo?
[fv-az95-172:65024] *** Process received signal ***
[fv-az95-172:65024] Signal: Aborted (6)
[fv-az95-172:65024] Signal code:  (-6)
[fv-az95-172:65024] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f85770ba210]
[fv-az95-172:65024] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f85770ba18b]
[fv-az95-172:65024] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f8577099859]
[fv-az95-172:65024] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f8577321911]
[fv-az95-172:65024] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f857732d38c]
[fv-az95-172:65024] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f857732d3f7]
[fv-az95-172:65024] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f857732d6fd]
[fv-az95-172:65024] [ 7] plumed_master(+0xf5b5)[0x55b7917245b5]
[fv-az95-172:65024] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f857709b0b3]
[fv-az95-172:65024] [ 9] plumed_master(+0xf8be)[0x55b7917248be]
[fv-az95-172:65024] *** End of error message ***
</pre>
{% endraw %}
