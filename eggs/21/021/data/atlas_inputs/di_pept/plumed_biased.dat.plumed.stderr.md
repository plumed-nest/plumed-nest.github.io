**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/di_pept/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: ATLAS LABEL=at REFERENCE=cluster_plumed.dat PACE=500 ARG=t1,t2 SIGMA=0.10 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=5.0 GRID_BIN=500 TEMP=300 TRUNCATE_GRIDS REGULARISE=1E-6 STATIC_WALL=0.0 ADAPTIVE_WALL=1.0
Maybe a missing space or a typo?
[fv-az1153-362:70165] *** Process received signal ***
[fv-az1153-362:70165] Signal: Aborted (6)
[fv-az1153-362:70165] Signal code:  (-6)
[fv-az1153-362:70165] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5a2d242520]
[fv-az1153-362:70165] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5a2d2969fc]
[fv-az1153-362:70165] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5a2d242476]
[fv-az1153-362:70165] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5a2d2287f3]
[fv-az1153-362:70165] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f5a2d6a4f26]
[fv-az1153-362:70165] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f5a2d6b6d9c]
[fv-az1153-362:70165] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f5a2d6b6e07]
[fv-az1153-362:70165] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5a2d6b70bb]
[fv-az1153-362:70165] [ 8] plumed(+0x12f48)[0x5614ed7dff48]
[fv-az1153-362:70165] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5a2d229d90]
[fv-az1153-362:70165] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5a2d229e40]
[fv-az1153-362:70165] [11] plumed(+0x131e5)[0x5614ed7e01e5]
[fv-az1153-362:70165] *** End of error message ***
</pre>
{% endraw %}
