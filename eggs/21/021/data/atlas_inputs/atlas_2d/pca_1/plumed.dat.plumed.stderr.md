**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_1/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=rr ARG=d1.x,d1.y REFERENCE=cluster.dat PACE=500 SIGMA=0.2 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=5.0 GRID_BIN=500 TEMP=1 TRUNCATE_GRIDS REGULARISE=0.00000001 STATIC_WALL=0.0 ADAPTIVE_WALL=1.0
Maybe a missing space or a typo?
[fv-az95-172:33770] *** Process received signal ***
[fv-az95-172:33770] Signal: Aborted (6)
[fv-az95-172:33770] Signal code:  (-6)
[fv-az95-172:33770] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fbb11b63210]
[fv-az95-172:33770] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fbb11b6318b]
[fv-az95-172:33770] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fbb11b42859]
[fv-az95-172:33770] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fbb11dca911]
[fv-az95-172:33770] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fbb11dd638c]
[fv-az95-172:33770] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fbb11dd63f7]
[fv-az95-172:33770] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fbb11dd66a9]
[fv-az95-172:33770] [ 7] plumed(+0xf47d)[0x557e5ac9c47d]
[fv-az95-172:33770] [ 8] plumed(+0x14004)[0x557e5aca1004]
[fv-az95-172:33770] [ 9] plumed(+0xf698)[0x557e5ac9c698]
[fv-az95-172:33770] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fbb11b440b3]
[fv-az95-172:33770] [11] plumed(+0xf76e)[0x557e5ac9c76e]
[fv-az95-172:33770] *** End of error message ***
</pre>
{% endraw %}
