**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/pca_2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=rr ARG=d1.x,d1.y,d1.z REFERENCE=cluster.dat PACE=500 SIGMA=0.2 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=5.0 GRID_BIN=500 TEMP=1 TRUNCATE_GRIDS REGULARISE=1E-8 ADAPTIVE_WALL=1.0 STATIC_WALL=0.0
Maybe a missing space or a typo?
[fv-az95-172:33854] *** Process received signal ***
[fv-az95-172:33854] Signal: Aborted (6)
[fv-az95-172:33854] Signal code:  (-6)
[fv-az95-172:33854] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fdb84b36210]
[fv-az95-172:33854] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fdb84b3618b]
[fv-az95-172:33854] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fdb84b15859]
[fv-az95-172:33854] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fdb84d9d911]
[fv-az95-172:33854] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fdb84da938c]
[fv-az95-172:33854] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fdb84da93f7]
[fv-az95-172:33854] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fdb84da96fd]
[fv-az95-172:33854] [ 7] plumed_master(+0xf5b5)[0x558b5d9d35b5]
[fv-az95-172:33854] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fdb84b170b3]
[fv-az95-172:33854] [ 9] plumed_master(+0xf8be)[0x558b5d9d38be]
[fv-az95-172:33854] *** End of error message ***
</pre>
{% endraw %}
