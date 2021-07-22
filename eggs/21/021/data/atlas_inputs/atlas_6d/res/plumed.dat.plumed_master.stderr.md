**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/res/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=at ARG=d1.x,d1.y,d1.z,d2.x,d2.y,d2.z REFERENCE=cluster.dat PACE=500 SIGMA=0.2 BIASFACTOR=15 HEIGHT=3.0 GRID_MAX=10.0 GRID_BIN=500 TEMP=1.0 TRUNCATE_GRIDS REGULARISE=1E-10 ADAPTIVE_WALL=1.0 STATIC_WALL=0.0
Maybe a missing space or a typo?
[fv-az95-172:33958] *** Process received signal ***
[fv-az95-172:33958] Signal: Aborted (6)
[fv-az95-172:33958] Signal code:  (-6)
[fv-az95-172:33958] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f6e5ce70210]
[fv-az95-172:33958] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f6e5ce7018b]
[fv-az95-172:33958] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f6e5ce4f859]
[fv-az95-172:33958] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f6e5d0d7911]
[fv-az95-172:33958] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f6e5d0e338c]
[fv-az95-172:33958] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f6e5d0e33f7]
[fv-az95-172:33958] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f6e5d0e36fd]
[fv-az95-172:33958] [ 7] plumed_master(+0xf5b5)[0x56302319c5b5]
[fv-az95-172:33958] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f6e5ce510b3]
[fv-az95-172:33958] [ 9] plumed_master(+0xf8be)[0x56302319c8be]
[fv-az95-172:33958] *** End of error message ***
</pre>
{% endraw %}
