**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/tetra_pept/plumed_biased.dat   
(download [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=at REFERENCE=cluster_plumed.dat PACE=500 ARG=t1,t2,t3,t4,t5,t6 SIGMA=0.1 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=3.5 GRID_BIN=500 TEMP=300 TRUNCATE_GRIDS REGULARISE=1E-12 STATIC_WALL=0.00 ADAPTIVE_WALL=1.00
Maybe a missing space or a typo?
[fv-az95-172:34000] *** Process received signal ***
[fv-az95-172:34000] Signal: Aborted (6)
[fv-az95-172:34000] Signal code:  (-6)
[fv-az95-172:34000] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f1517a87210]
[fv-az95-172:34000] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f1517a8718b]
[fv-az95-172:34000] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f1517a66859]
[fv-az95-172:34000] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f1517cee911]
[fv-az95-172:34000] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f1517cfa38c]
[fv-az95-172:34000] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f1517cfa3f7]
[fv-az95-172:34000] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f1517cfa6a9]
[fv-az95-172:34000] [ 7] plumed(+0xf47d)[0x55a2b2f1e47d]
[fv-az95-172:34000] [ 8] plumed(+0x14004)[0x55a2b2f23004]
[fv-az95-172:34000] [ 9] plumed(+0xf698)[0x55a2b2f1e698]
[fv-az95-172:34000] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f1517a680b3]
[fv-az95-172:34000] [11] plumed(+0xf76e)[0x55a2b2f1e76e]
[fv-az95-172:34000] *** End of error message ***
</pre>
{% endraw %}
