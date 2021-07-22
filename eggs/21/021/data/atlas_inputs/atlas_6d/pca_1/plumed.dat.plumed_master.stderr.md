**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/pca_1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=at ARG=d1.x,d1.y,d1.z,d2.x,d2.y,d2.z REFERENCE=cluster.dat PACE=500 SIGMA=0.2 BIASFACTOR=15 HEIGHT=3.0 GRID_MAX=7.0 GRID_BIN=500 TEMP=1 TRUNCATE_GRIDS REGULARISE=1E-10 ADAPTIVE_WALL=1.0 STATIC_WALL=0.0
Maybe a missing space or a typo?
[fv-az95-172:33903] *** Process received signal ***
[fv-az95-172:33903] Signal: Aborted (6)
[fv-az95-172:33903] Signal code:  (-6)
[fv-az95-172:33903] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f586ec36210]
[fv-az95-172:33903] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f586ec3618b]
[fv-az95-172:33903] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f586ec15859]
[fv-az95-172:33903] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f586ee9d911]
[fv-az95-172:33903] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f586eea938c]
[fv-az95-172:33903] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f586eea93f7]
[fv-az95-172:33903] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f586eea96fd]
[fv-az95-172:33903] [ 7] plumed_master(+0xf5b5)[0x55aa9ac595b5]
[fv-az95-172:33903] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f586ec170b3]
[fv-az95-172:33903] [ 9] plumed_master(+0xf8be)[0x55aa9ac598be]
[fv-az95-172:33903] *** End of error message ***
</pre>
{% endraw %}
