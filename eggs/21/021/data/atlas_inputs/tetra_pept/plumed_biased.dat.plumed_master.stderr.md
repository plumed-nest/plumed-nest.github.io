**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/tetra_pept/plumed_biased.dat   
(download [zipped raw stdout](plumed_biased.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=at REFERENCE=cluster_plumed.dat PACE=500 ARG=t1,t2,t3,t4,t5,t6 SIGMA=0.1 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=3.5 GRID_BIN=500 TEMP=300 TRUNCATE_GRIDS REGULARISE=1E-12 STATIC_WALL=0.00 ADAPTIVE_WALL=1.00
Maybe a missing space or a typo?
[fv-az95-172:34008] *** Process received signal ***
[fv-az95-172:34008] Signal: Aborted (6)
[fv-az95-172:34008] Signal code:  (-6)
[fv-az95-172:34008] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f554d92c210]
[fv-az95-172:34008] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f554d92c18b]
[fv-az95-172:34008] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f554d90b859]
[fv-az95-172:34008] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f554db93911]
[fv-az95-172:34008] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f554db9f38c]
[fv-az95-172:34008] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f554db9f3f7]
[fv-az95-172:34008] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f554db9f6fd]
[fv-az95-172:34008] [ 7] plumed_master(+0xf5b5)[0x5568aa9cb5b5]
[fv-az95-172:34008] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f554d90d0b3]
[fv-az95-172:34008] [ 9] plumed_master(+0xf8be)[0x5568aa9cb8be]
[fv-az95-172:34008] *** End of error message ***
</pre>
{% endraw %}
