**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az1433-905:68910] *** Process received signal ***
[fv-az1433-905:68910] Signal: Aborted (6)
[fv-az1433-905:68910] Signal code:  (-6)
[fv-az1433-905:68910] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f08a8042520]
[fv-az1433-905:68910] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f08a80969fc]
[fv-az1433-905:68910] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f08a8042476]
[fv-az1433-905:68910] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f08a80287f3]
[fv-az1433-905:68910] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f08a84a4f26]
[fv-az1433-905:68910] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f08a84b6d9c]
[fv-az1433-905:68910] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f08a84b6e07]
[fv-az1433-905:68910] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f08a84b70bb]
[fv-az1433-905:68910] [ 8] plumed_master(+0x12e7f)[0x55c977991e7f]
[fv-az1433-905:68910] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f08a8029d90]
[fv-az1433-905:68910] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f08a8029e40]
[fv-az1433-905:68910] [11] plumed_master(+0x13115)[0x55c977992115]
[fv-az1433-905:68910] *** End of error message ***
</pre>
{% endraw %}
