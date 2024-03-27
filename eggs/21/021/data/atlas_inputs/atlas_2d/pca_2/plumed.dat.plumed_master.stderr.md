**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: ATLAS LABEL=rr ARG=d1.x,d1.y REFERENCE=cluster.dat PACE=500 SIGMA=0.20 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=6.0 GRID_BIN=600 TEMP=1 TRUNCATE_GRIDS REGULARISE=0.00000001 STATIC_WALL=0.0 ADAPTIVE_WALL=1.0
Maybe a missing space or a typo?
[fv-az1153-362:69956] *** Process received signal ***
[fv-az1153-362:69956] Signal: Aborted (6)
[fv-az1153-362:69956] Signal code:  (-6)
[fv-az1153-362:69956] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f23f8a42520]
[fv-az1153-362:69956] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f23f8a969fc]
[fv-az1153-362:69956] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f23f8a42476]
[fv-az1153-362:69956] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f23f8a287f3]
[fv-az1153-362:69956] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f23f8ea4f26]
[fv-az1153-362:69956] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f23f8eb6d9c]
[fv-az1153-362:69956] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f23f8eb6e07]
[fv-az1153-362:69956] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f23f8eb70bb]
[fv-az1153-362:69956] [ 8] plumed_master(+0x12e7f)[0x55d0b94b3e7f]
[fv-az1153-362:69956] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f23f8a29d90]
[fv-az1153-362:69956] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f23f8a29e40]
[fv-az1153-362:69956] [11] plumed_master(+0x13115)[0x55d0b94b4115]
[fv-az1153-362:69956] *** End of error message ***
</pre>
{% endraw %}
