**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/di_pept/plumed_biased.dat   
(download [zipped raw stdout](plumed_biased.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=at REFERENCE=cluster_plumed.dat PACE=500 ARG=t1,t2 SIGMA=0.10 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=5.0 GRID_BIN=500 TEMP=300 TRUNCATE_GRIDS REGULARISE=1E-6 STATIC_WALL=0.0 ADAPTIVE_WALL=1.0
Maybe a missing space or a typo?
[fv-az95-172:33984] *** Process received signal ***
[fv-az95-172:33984] Signal: Aborted (6)
[fv-az95-172:33984] Signal code:  (-6)
[fv-az95-172:33984] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f2ebbca8210]
[fv-az95-172:33984] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f2ebbca818b]
[fv-az95-172:33984] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f2ebbc87859]
[fv-az95-172:33984] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f2ebbf0f911]
[fv-az95-172:33984] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f2ebbf1b38c]
[fv-az95-172:33984] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f2ebbf1b3f7]
[fv-az95-172:33984] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7f2ebbf1b6fd]
[fv-az95-172:33984] [ 7] plumed_master(+0xf5b5)[0x557d35d6c5b5]
[fv-az95-172:33984] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f2ebbc890b3]
[fv-az95-172:33984] [ 9] plumed_master(+0xf8be)[0x557d35d6c8be]
[fv-az95-172:33984] *** End of error message ***
</pre>
{% endraw %}
