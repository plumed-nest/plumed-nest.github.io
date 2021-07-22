**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/pca_2/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=at ARG=d1.x,d1.y,d1.z,d2.x,d2.y,d2.z REFERENCE=cluster.dat PACE=500 SIGMA=0.2 BIASFACTOR=15 HEIGHT=3.0 GRID_MAX=15.0 GRID_BIN=750 TEMP=1.0 TRUNCATE_GRIDS REGULARISE=1E-11 ADAPTIVE_WALL=1.0 STATIC_WALL=0.0
Maybe a missing space or a typo?
[fv-az95-172:33921] *** Process received signal ***
[fv-az95-172:33921] Signal: Aborted (6)
[fv-az95-172:33921] Signal code:  (-6)
[fv-az95-172:33921] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f46614e1210]
[fv-az95-172:33921] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f46614e118b]
[fv-az95-172:33921] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f46614c0859]
[fv-az95-172:33921] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f4661748911]
[fv-az95-172:33921] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f466175438c]
[fv-az95-172:33921] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f46617543f7]
[fv-az95-172:33921] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f46617546a9]
[fv-az95-172:33921] [ 7] plumed(+0xf47d)[0x55af10afb47d]
[fv-az95-172:33921] [ 8] plumed(+0x14004)[0x55af10b00004]
[fv-az95-172:33921] [ 9] plumed(+0xf698)[0x55af10afb698]
[fv-az95-172:33921] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f46614c20b3]
[fv-az95-172:33921] [11] plumed(+0xf76e)[0x55af10afb76e]
[fv-az95-172:33921] *** End of error message ***
</pre>
{% endraw %}
