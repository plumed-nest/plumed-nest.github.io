**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=rr ARG=d1.x,d1.y REFERENCE=cluster.dat PACE=500 SIGMA=0.2 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=5.0 GRID_BIN=500 TEMP=1 TRUNCATE_GRIDS REGULARISE=0.00000001 STATIC_WALL=0.0 ADAPTIVE_WALL=1.0
Maybe a missing space or a typo?
[fv-az95-172:33780] *** Process received signal ***
[fv-az95-172:33780] Signal: Aborted (6)
[fv-az95-172:33780] Signal code:  (-6)
[fv-az95-172:33780] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7ff993e8e210]
[fv-az95-172:33780] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7ff993e8e18b]
[fv-az95-172:33780] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7ff993e6d859]
[fv-az95-172:33780] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7ff9940f5911]
[fv-az95-172:33780] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7ff99410138c]
[fv-az95-172:33780] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7ff9941013f7]
[fv-az95-172:33780] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7ff9941016fd]
[fv-az95-172:33780] [ 7] plumed_master(+0xf5b5)[0x5599c5bc55b5]
[fv-az95-172:33780] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7ff993e6f0b3]
[fv-az95-172:33780] [ 9] plumed_master(+0xf8be)[0x5599c5bc58be]
[fv-az95-172:33780] *** End of error message ***
</pre>
{% endraw %}
