**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/res/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: ATLAS LABEL=at ARG=d1.x,d1.y,d1.z,d2.x,d2.y,d2.z REFERENCE=cluster.dat PACE=500 SIGMA=0.2 BIASFACTOR=15 HEIGHT=3.0 GRID_MAX=10.0 GRID_BIN=500 TEMP=1.0 TRUNCATE_GRIDS REGULARISE=1E-10 ADAPTIVE_WALL=1.0 STATIC_WALL=0.0
Maybe a missing space or a typo?
[fv-az1215-453:06584] *** Process received signal ***
[fv-az1215-453:06584] Signal: Aborted (6)
[fv-az1215-453:06584] Signal code:  (-6)
[fv-az1215-453:06584] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe0cbc42520]
[fv-az1215-453:06584] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe0cbc969fc]
[fv-az1215-453:06584] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe0cbc42476]
[fv-az1215-453:06584] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe0cbc287f3]
[fv-az1215-453:06584] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe0cc0a2b9e]
[fv-az1215-453:06584] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe0cc0ae20c]
[fv-az1215-453:06584] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe0cc0ae277]
[fv-az1215-453:06584] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe0cc0ae52b]
[fv-az1215-453:06584] [ 8] plumed(+0x12f48)[0x556ad6dd6f48]
[fv-az1215-453:06584] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe0cbc29d90]
[fv-az1215-453:06584] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe0cbc29e40]
[fv-az1215-453:06584] [11] plumed(+0x131e5)[0x556ad6dd71e5]
[fv-az1215-453:06584] *** End of error message ***
</pre>
{% endraw %}
