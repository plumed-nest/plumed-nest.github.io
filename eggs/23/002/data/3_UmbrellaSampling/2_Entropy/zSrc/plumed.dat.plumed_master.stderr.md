**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  3_UmbrellaSampling/2_Entropy/zSrc/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1433-905:68692] *** Process received signal ***
[fv-az1433-905:68692] Signal: Aborted (6)
[fv-az1433-905:68692] Signal code:  (-6)
[fv-az1433-905:68692] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fde11242520]
[fv-az1433-905:68692] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fde112969fc]
[fv-az1433-905:68692] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fde11242476]
[fv-az1433-905:68692] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fde112287f3]
[fv-az1433-905:68692] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fde116a4f26]
[fv-az1433-905:68692] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fde116b6d9c]
[fv-az1433-905:68692] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fde116b6e07]
[fv-az1433-905:68692] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fde116b70bb]
[fv-az1433-905:68692] [ 8] plumed_master(+0x12e7f)[0x55a234372e7f]
[fv-az1433-905:68692] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fde11229d90]
[fv-az1433-905:68692] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fde11229e40]
[fv-az1433-905:68692] [11] plumed_master(+0x13115)[0x55a234373115]
[fv-az1433-905:68692] *** End of error message ***
</pre>
{% endraw %}
