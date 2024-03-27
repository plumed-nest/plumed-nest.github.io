**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az1433-905:68902] *** Process received signal ***
[fv-az1433-905:68902] Signal: Aborted (6)
[fv-az1433-905:68902] Signal code:  (-6)
[fv-az1433-905:68902] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fef6aa42520]
[fv-az1433-905:68902] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fef6aa969fc]
[fv-az1433-905:68902] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fef6aa42476]
[fv-az1433-905:68902] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fef6aa287f3]
[fv-az1433-905:68902] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fef6aea4f26]
[fv-az1433-905:68902] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fef6aeb6d9c]
[fv-az1433-905:68902] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fef6aeb6e07]
[fv-az1433-905:68902] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fef6aeb70bb]
[fv-az1433-905:68902] [ 8] plumed(+0x12f48)[0x55f96151bf48]
[fv-az1433-905:68902] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fef6aa29d90]
[fv-az1433-905:68902] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fef6aa29e40]
[fv-az1433-905:68902] [11] plumed(+0x131e5)[0x55f96151c1e5]
[fv-az1433-905:68902] *** End of error message ***
</pre>
{% endraw %}
