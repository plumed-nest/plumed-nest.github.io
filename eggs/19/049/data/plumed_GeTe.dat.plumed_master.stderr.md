**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:302) void PLMD::Action::error(const string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[fv-az1433-905:72085] *** Process received signal ***
[fv-az1433-905:72085] Signal: Aborted (6)
[fv-az1433-905:72085] Signal code:  (-6)
[fv-az1433-905:72085] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9217242520]
[fv-az1433-905:72085] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f92172969fc]
[fv-az1433-905:72085] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9217242476]
[fv-az1433-905:72085] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f92172287f3]
[fv-az1433-905:72085] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f92176a4f26]
[fv-az1433-905:72085] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f92176b6d9c]
[fv-az1433-905:72085] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f92176b6e07]
[fv-az1433-905:72085] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f92176b70bb]
[fv-az1433-905:72085] [ 8] plumed_master(+0x12e7f)[0x556062adbe7f]
[fv-az1433-905:72085] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9217229d90]
[fv-az1433-905:72085] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9217229e40]
[fv-az1433-905:72085] [11] plumed_master(+0x13115)[0x556062adc115]
[fv-az1433-905:72085] *** End of error message ***
</pre>
{% endraw %}
