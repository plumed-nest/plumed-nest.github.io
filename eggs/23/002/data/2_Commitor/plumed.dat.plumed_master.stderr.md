**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  2_Commitor/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1433-905:68628] *** Process received signal ***
[fv-az1433-905:68628] Signal: Aborted (6)
[fv-az1433-905:68628] Signal code:  (-6)
[fv-az1433-905:68628] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f90b0e42520]
[fv-az1433-905:68628] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f90b0e969fc]
[fv-az1433-905:68628] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f90b0e42476]
[fv-az1433-905:68628] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f90b0e287f3]
[fv-az1433-905:68628] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f90b12a4f26]
[fv-az1433-905:68628] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f90b12b6d9c]
[fv-az1433-905:68628] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f90b12b6e07]
[fv-az1433-905:68628] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f90b12b70bb]
[fv-az1433-905:68628] [ 8] plumed_master(+0x12e7f)[0x5648d4a65e7f]
[fv-az1433-905:68628] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f90b0e29d90]
[fv-az1433-905:68628] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f90b0e29e40]
[fv-az1433-905:68628] [11] plumed_master(+0x13115)[0x5648d4a66115]
[fv-az1433-905:68628] *** End of error message ***
</pre>
{% endraw %}
