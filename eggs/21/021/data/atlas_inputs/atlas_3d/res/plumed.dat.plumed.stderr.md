**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/res/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=rr ARG=d1.x,d1.y,d1.z REFERENCE=cluster.dat PACE=500 SIGMA=0.2 BIASFACTOR=10 HEIGHT=3.0 GRID_MAX=5.0 GRID_BIN=500 TEMP=1 TRUNCATE_GRIDS REGULARISE=1E-8 ADAPTIVE_WALL=1.0 STATIC_WALL=0.0
Maybe a missing space or a typo?
[fv-az95-172:33871] *** Process received signal ***
[fv-az95-172:33871] Signal: Aborted (6)
[fv-az95-172:33871] Signal code:  (-6)
[fv-az95-172:33871] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fcdf8cb3210]
[fv-az95-172:33871] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fcdf8cb318b]
[fv-az95-172:33871] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fcdf8c92859]
[fv-az95-172:33871] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fcdf8f1a911]
[fv-az95-172:33871] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fcdf8f2638c]
[fv-az95-172:33871] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fcdf8f263f7]
[fv-az95-172:33871] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fcdf8f266a9]
[fv-az95-172:33871] [ 7] plumed(+0xf47d)[0x55d6bfe2347d]
[fv-az95-172:33871] [ 8] plumed(+0x14004)[0x55d6bfe28004]
[fv-az95-172:33871] [ 9] plumed(+0xf698)[0x55d6bfe23698]
[fv-az95-172:33871] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fcdf8c940b3]
[fv-az95-172:33871] [11] plumed(+0xf76e)[0x55d6bfe2376e]
[fv-az95-172:33871] *** End of error message ***
</pre>
{% endraw %}
