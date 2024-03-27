**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: ATLAS LABEL=atlas ARG=d1.x,d1.y,d1.z,d2.x,d2.y,d2.z REFERENCE=cluster.dat PACE=500 SIGMA=0.2 BIASFACTOR=10 HEIGHT=2.0 GRID_MAX=5.0 GRID_BIN=500 TEMP=1 TRUNCATE_GRIDS REGULARISE=1E-8 ADAPTIVE_WALL=1.0 STATIC_WALL=0.0
Maybe a missing space or a typo?
[fv-az1153-362:69851] *** Process received signal ***
[fv-az1153-362:69851] Signal: Aborted (6)
[fv-az1153-362:69851] Signal code:  (-6)
[fv-az1153-362:69851] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f634f842520]
[fv-az1153-362:69851] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f634f8969fc]
[fv-az1153-362:69851] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f634f842476]
[fv-az1153-362:69851] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f634f8287f3]
[fv-az1153-362:69851] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f634fca4f26]
[fv-az1153-362:69851] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f634fcb6d9c]
[fv-az1153-362:69851] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f634fcb6e07]
[fv-az1153-362:69851] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f634fcb70bb]
[fv-az1153-362:69851] [ 8] plumed(+0x12f48)[0x55ca8e7abf48]
[fv-az1153-362:69851] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f634f829d90]
[fv-az1153-362:69851] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f634f829e40]
[fv-az1153-362:69851] [11] plumed(+0x131e5)[0x55ca8e7ac1e5]
[fv-az1153-362:69851] *** End of error message ***
</pre>
{% endraw %}
