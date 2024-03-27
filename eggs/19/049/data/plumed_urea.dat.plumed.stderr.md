**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action DISTANCES with label m1 : cannot understand the following words from the input line : LOCATION1=1, LOCATION2=9, COMPONENTS
[fv-az1433-905:72138] *** Process received signal ***
[fv-az1433-905:72138] Signal: Aborted (6)
[fv-az1433-905:72138] Signal code:  (-6)
[fv-az1433-905:72138] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1495a42520]
[fv-az1433-905:72138] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1495a969fc]
[fv-az1433-905:72138] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1495a42476]
[fv-az1433-905:72138] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1495a287f3]
[fv-az1433-905:72138] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f1495ea4f26]
[fv-az1433-905:72138] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f1495eb6d9c]
[fv-az1433-905:72138] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f1495eb6e07]
[fv-az1433-905:72138] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1495eb70bb]
[fv-az1433-905:72138] [ 8] plumed(+0x12f48)[0x5594664f5f48]
[fv-az1433-905:72138] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1495a29d90]
[fv-az1433-905:72138] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1495a29e40]
[fv-az1433-905:72138] [11] plumed(+0x131e5)[0x5594664f61e5]
[fv-az1433-905:72138] *** End of error message ***
</pre>
{% endraw %}
