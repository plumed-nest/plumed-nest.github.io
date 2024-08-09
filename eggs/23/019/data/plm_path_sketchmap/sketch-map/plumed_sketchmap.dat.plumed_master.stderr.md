**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[fv-az1490-855:04657] *** Process received signal ***
[fv-az1490-855:04657] Signal: Aborted (6)
[fv-az1490-855:04657] Signal code:  (-6)
[fv-az1490-855:04657] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe8b4242520]
[fv-az1490-855:04657] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe8b42969fc]
[fv-az1490-855:04657] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe8b4242476]
[fv-az1490-855:04657] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe8b42287f3]
[fv-az1490-855:04657] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe8b46a2b9e]
[fv-az1490-855:04657] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe8b46ae20c]
[fv-az1490-855:04657] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe8b46ae277]
[fv-az1490-855:04657] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe8b46ae52b]
[fv-az1490-855:04657] [ 8] plumed_master(+0x14274)[0x55c1217ea274]
[fv-az1490-855:04657] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe8b4229d90]
[fv-az1490-855:04657] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe8b4229e40]
[fv-az1490-855:04657] [11] plumed_master(+0x14ed5)[0x55c1217eaed5]
[fv-az1490-855:04657] *** End of error message ***
</pre>
{% endraw %}
