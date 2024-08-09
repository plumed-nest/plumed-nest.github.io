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
[fv-az1446-488:06799] *** Process received signal ***
[fv-az1446-488:06799] Signal: Aborted (6)
[fv-az1446-488:06799] Signal code:  (-6)
[fv-az1446-488:06799] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9325042520]
[fv-az1446-488:06799] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f93250969fc]
[fv-az1446-488:06799] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9325042476]
[fv-az1446-488:06799] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f93250287f3]
[fv-az1446-488:06799] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f93254a2b9e]
[fv-az1446-488:06799] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f93254ae20c]
[fv-az1446-488:06799] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f93254ae277]
[fv-az1446-488:06799] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f93254ae52b]
[fv-az1446-488:06799] [ 8] plumed(+0x12f48)[0x557d47ac8f48]
[fv-az1446-488:06799] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9325029d90]
[fv-az1446-488:06799] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9325029e40]
[fv-az1446-488:06799] [11] plumed(+0x131e5)[0x557d47ac91e5]
[fv-az1446-488:06799] *** End of error message ***
</pre>
{% endraw %}
