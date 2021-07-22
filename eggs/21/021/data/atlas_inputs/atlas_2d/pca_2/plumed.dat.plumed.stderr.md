**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=rr ARG=d1.x,d1.y REFERENCE=cluster.dat PACE=500 SIGMA=0.20 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=6.0 GRID_BIN=600 TEMP=1 TRUNCATE_GRIDS REGULARISE=0.00000001 STATIC_WALL=0.0 ADAPTIVE_WALL=1.0
Maybe a missing space or a typo?
[fv-az95-172:33797] *** Process received signal ***
[fv-az95-172:33797] Signal: Aborted (6)
[fv-az95-172:33797] Signal code:  (-6)
[fv-az95-172:33797] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fc618720210]
[fv-az95-172:33797] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fc61872018b]
[fv-az95-172:33797] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fc6186ff859]
[fv-az95-172:33797] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fc618987911]
[fv-az95-172:33797] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fc61899338c]
[fv-az95-172:33797] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fc6189933f7]
[fv-az95-172:33797] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fc6189936a9]
[fv-az95-172:33797] [ 7] plumed(+0xf47d)[0x55803282947d]
[fv-az95-172:33797] [ 8] plumed(+0x14004)[0x55803282e004]
[fv-az95-172:33797] [ 9] plumed(+0xf698)[0x558032829698]
[fv-az95-172:33797] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fc6187010b3]
[fv-az95-172:33797] [11] plumed(+0xf76e)[0x55803282976e]
[fv-az95-172:33797] *** End of error message ***
</pre>
{% endraw %}
