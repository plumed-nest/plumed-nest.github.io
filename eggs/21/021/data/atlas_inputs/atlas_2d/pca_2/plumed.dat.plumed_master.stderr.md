**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:736, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=rr ARG=d1.x,d1.y REFERENCE=cluster.dat PACE=500 SIGMA=0.20 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=6.0 GRID_BIN=600 TEMP=1 TRUNCATE_GRIDS REGULARISE=0.00000001 STATIC_WALL=0.0 ADAPTIVE_WALL=1.0
Maybe a missing space or a typo?
[fv-az95-172:33805] *** Process received signal ***
[fv-az95-172:33805] Signal: Aborted (6)
[fv-az95-172:33805] Signal code:  (-6)
[fv-az95-172:33805] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fbda89c8210]
[fv-az95-172:33805] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fbda89c818b]
[fv-az95-172:33805] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fbda89a7859]
[fv-az95-172:33805] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fbda8c2f911]
[fv-az95-172:33805] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fbda8c3b38c]
[fv-az95-172:33805] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fbda8c3b3f7]
[fv-az95-172:33805] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7fbda8c3b6fd]
[fv-az95-172:33805] [ 7] plumed_master(+0xf5b5)[0x55a4af1c05b5]
[fv-az95-172:33805] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fbda89a90b3]
[fv-az95-172:33805] [ 9] plumed_master(+0xf8be)[0x55a4af1c08be]
[fv-az95-172:33805] *** End of error message ***
</pre>
{% endraw %}
