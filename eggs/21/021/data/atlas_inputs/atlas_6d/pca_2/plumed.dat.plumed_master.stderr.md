**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/pca_2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=at ARG=d1.x,d1.y,d1.z,d2.x,d2.y,d2.z REFERENCE=cluster.dat PACE=500 SIGMA=0.2 BIASFACTOR=15 HEIGHT=3.0 GRID_MAX=15.0 GRID_BIN=750 TEMP=1.0 TRUNCATE_GRIDS REGULARISE=1E-11 ADAPTIVE_WALL=1.0 STATIC_WALL=0.0
Maybe a missing space or a typo?
[fv-az95-172:33930] *** Process received signal ***
[fv-az95-172:33930] Signal: Aborted (6)
[fv-az95-172:33930] Signal code:  (-6)
[fv-az95-172:33930] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7feae44bf210]
[fv-az95-172:33930] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7feae44bf18b]
[fv-az95-172:33930] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7feae449e859]
[fv-az95-172:33930] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7feae4726911]
[fv-az95-172:33930] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7feae473238c]
[fv-az95-172:33930] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7feae47323f7]
[fv-az95-172:33930] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7feae47326fd]
[fv-az95-172:33930] [ 7] plumed_master(+0xf5b5)[0x55b68a47b5b5]
[fv-az95-172:33930] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7feae44a00b3]
[fv-az95-172:33930] [ 9] plumed_master(+0xf8be)[0x55b68a47b8be]
[fv-az95-172:33930] *** End of error message ***
</pre>
{% endraw %}
