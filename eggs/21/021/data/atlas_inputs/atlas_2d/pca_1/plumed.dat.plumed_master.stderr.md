**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: ATLAS LABEL=rr ARG=d1.x,d1.y REFERENCE=cluster.dat PACE=500 SIGMA=0.2 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=5.0 GRID_BIN=500 TEMP=1 TRUNCATE_GRIDS REGULARISE=0.00000001 STATIC_WALL=0.0 ADAPTIVE_WALL=1.0
Maybe a missing space or a typo?
[fv-az1153-362:69924] *** Process received signal ***
[fv-az1153-362:69924] Signal: Aborted (6)
[fv-az1153-362:69924] Signal code:  (-6)
[fv-az1153-362:69924] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5680042520]
[fv-az1153-362:69924] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f56800969fc]
[fv-az1153-362:69924] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5680042476]
[fv-az1153-362:69924] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f56800287f3]
[fv-az1153-362:69924] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f56804a4f26]
[fv-az1153-362:69924] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f56804b6d9c]
[fv-az1153-362:69924] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f56804b6e07]
[fv-az1153-362:69924] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f56804b70bb]
[fv-az1153-362:69924] [ 8] plumed_master(+0x12e7f)[0x55fef7cf1e7f]
[fv-az1153-362:69924] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5680029d90]
[fv-az1153-362:69924] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5680029e40]
[fv-az1153-362:69924] [11] plumed_master(+0x13115)[0x55fef7cf2115]
[fv-az1153-362:69924] *** End of error message ***
</pre>
{% endraw %}
