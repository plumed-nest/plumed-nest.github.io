**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[fv-az1433-905:67652] *** Process received signal ***
[fv-az1433-905:67652] Signal: Aborted (6)
[fv-az1433-905:67652] Signal code:  (-6)
[fv-az1433-905:67652] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8505042520]
[fv-az1433-905:67652] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f85050969fc]
[fv-az1433-905:67652] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8505042476]
[fv-az1433-905:67652] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f85050287f3]
[fv-az1433-905:67652] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f85054a4f26]
[fv-az1433-905:67652] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f85054b6d9c]
[fv-az1433-905:67652] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f85054b6e07]
[fv-az1433-905:67652] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f85054b70bb]
[fv-az1433-905:67652] [ 8] plumed_master(+0x12e7f)[0x5601e115de7f]
[fv-az1433-905:67652] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8505029d90]
[fv-az1433-905:67652] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8505029e40]
[fv-az1433-905:67652] [11] plumed_master(+0x13115)[0x5601e115e115]
[fv-az1433-905:67652] *** End of error message ***
</pre>
{% endraw %}
