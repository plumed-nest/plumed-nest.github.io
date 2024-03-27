**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[fv-az1433-905:68597] *** Process received signal ***
[fv-az1433-905:68597] Signal: Aborted (6)
[fv-az1433-905:68597] Signal code:  (-6)
[fv-az1433-905:68597] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f243a642520]
[fv-az1433-905:68597] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f243a6969fc]
[fv-az1433-905:68597] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f243a642476]
[fv-az1433-905:68597] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f243a6287f3]
[fv-az1433-905:68597] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f243aaa4f26]
[fv-az1433-905:68597] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f243aab6d9c]
[fv-az1433-905:68597] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f243aab6e07]
[fv-az1433-905:68597] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f243aab70bb]
[fv-az1433-905:68597] [ 8] plumed_master(+0x12e7f)[0x55c35af2fe7f]
[fv-az1433-905:68597] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f243a629d90]
[fv-az1433-905:68597] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f243a629e40]
[fv-az1433-905:68597] [11] plumed_master(+0x13115)[0x55c35af30115]
[fv-az1433-905:68597] *** End of error message ***
</pre>
{% endraw %}
