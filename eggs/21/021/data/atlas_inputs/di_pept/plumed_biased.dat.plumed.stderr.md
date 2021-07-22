**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/di_pept/plumed_biased.dat   
(download [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: ATLAS LABEL=at REFERENCE=cluster_plumed.dat PACE=500 ARG=t1,t2 SIGMA=0.10 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=5.0 GRID_BIN=500 TEMP=300 TRUNCATE_GRIDS REGULARISE=1E-6 STATIC_WALL=0.0 ADAPTIVE_WALL=1.0
Maybe a missing space or a typo?
[fv-az95-172:33976] *** Process received signal ***
[fv-az95-172:33976] Signal: Aborted (6)
[fv-az95-172:33976] Signal code:  (-6)
[fv-az95-172:33976] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7fd2cb3dd210]
[fv-az95-172:33976] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7fd2cb3dd18b]
[fv-az95-172:33976] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7fd2cb3bc859]
[fv-az95-172:33976] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7fd2cb644911]
[fv-az95-172:33976] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7fd2cb65038c]
[fv-az95-172:33976] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7fd2cb6503f7]
[fv-az95-172:33976] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7fd2cb6506a9]
[fv-az95-172:33976] [ 7] plumed(+0xf47d)[0x563a5f74c47d]
[fv-az95-172:33976] [ 8] plumed(+0x14004)[0x563a5f751004]
[fv-az95-172:33976] [ 9] plumed(+0xf698)[0x563a5f74c698]
[fv-az95-172:33976] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7fd2cb3be0b3]
[fv-az95-172:33976] [11] plumed(+0xf76e)[0x563a5f74c76e]
[fv-az95-172:33976] *** End of error message ***
</pre>
{% endraw %}
