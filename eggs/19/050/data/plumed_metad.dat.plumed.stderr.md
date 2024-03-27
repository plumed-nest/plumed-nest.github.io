**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_metad.dat   
Download: [zipped raw stdout](plumed_metad.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_metad.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action DISTANCE_FROM_CONTOUR with label cont : keyword DATA is compulsory for this action
[fv-az1153-362:71864] *** Process received signal ***
[fv-az1153-362:71864] Signal: Aborted (6)
[fv-az1153-362:71864] Signal code:  (-6)
[fv-az1153-362:71864] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fddd0042520]
[fv-az1153-362:71864] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fddd00969fc]
[fv-az1153-362:71864] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fddd0042476]
[fv-az1153-362:71864] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fddd00287f3]
[fv-az1153-362:71864] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fddd04a4f26]
[fv-az1153-362:71864] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fddd04b6d9c]
[fv-az1153-362:71864] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fddd04b6e07]
[fv-az1153-362:71864] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fddd04b70bb]
[fv-az1153-362:71864] [ 8] plumed(+0x12f48)[0x55bea39cff48]
[fv-az1153-362:71864] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fddd0029d90]
[fv-az1153-362:71864] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fddd0029e40]
[fv-az1153-362:71864] [11] plumed(+0x131e5)[0x55bea39d01e5]
[fv-az1153-362:71864] *** End of error message ***
</pre>
{% endraw %}
