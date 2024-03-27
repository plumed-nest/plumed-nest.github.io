**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[fv-az1433-905:72146] *** Process received signal ***
[fv-az1433-905:72146] Signal: Aborted (6)
[fv-az1433-905:72146] Signal code:  (-6)
[fv-az1433-905:72146] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd703642520]
[fv-az1433-905:72146] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd7036969fc]
[fv-az1433-905:72146] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd703642476]
[fv-az1433-905:72146] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd7036287f3]
[fv-az1433-905:72146] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fd703aa4f26]
[fv-az1433-905:72146] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fd703ab6d9c]
[fv-az1433-905:72146] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fd703ab6e07]
[fv-az1433-905:72146] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd703ab70bb]
[fv-az1433-905:72146] [ 8] plumed_master(+0x12e7f)[0x5637528dee7f]
[fv-az1433-905:72146] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd703629d90]
[fv-az1433-905:72146] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd703629e40]
[fv-az1433-905:72146] [11] plumed_master(+0x13115)[0x5637528df115]
[fv-az1433-905:72146] *** End of error message ***
</pre>
{% endraw %}
