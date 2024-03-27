**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/tetra_pept/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: ATLAS LABEL=at REFERENCE=cluster_plumed.dat PACE=500 ARG=t1,t2,t3,t4,t5,t6 SIGMA=0.1 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=3.5 GRID_BIN=500 TEMP=300 TRUNCATE_GRIDS REGULARISE=1E-12 STATIC_WALL=0.00 ADAPTIVE_WALL=1.00
Maybe a missing space or a typo?
[fv-az1153-362:70196] *** Process received signal ***
[fv-az1153-362:70196] Signal: Aborted (6)
[fv-az1153-362:70196] Signal code:  (-6)
[fv-az1153-362:70196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8a34e42520]
[fv-az1153-362:70196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8a34e969fc]
[fv-az1153-362:70196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8a34e42476]
[fv-az1153-362:70196] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8a34e287f3]
[fv-az1153-362:70196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f8a352a4f26]
[fv-az1153-362:70196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f8a352b6d9c]
[fv-az1153-362:70196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f8a352b6e07]
[fv-az1153-362:70196] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8a352b70bb]
[fv-az1153-362:70196] [ 8] plumed(+0x12f48)[0x56340636ff48]
[fv-az1153-362:70196] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8a34e29d90]
[fv-az1153-362:70196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8a34e29e40]
[fv-az1153-362:70196] [11] plumed(+0x131e5)[0x5634063701e5]
[fv-az1153-362:70196] *** End of error message ***
</pre>
{% endraw %}
