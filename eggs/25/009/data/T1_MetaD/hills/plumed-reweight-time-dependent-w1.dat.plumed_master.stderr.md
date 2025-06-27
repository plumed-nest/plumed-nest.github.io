**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w1.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:61848] *** Process received signal ***
[pkrvmbietmlfzoi:61848] Signal: Aborted (6)
[pkrvmbietmlfzoi:61848] Signal code:  (-6)
[pkrvmbietmlfzoi:61848] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e07645330]
[pkrvmbietmlfzoi:61848] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e0769eb2c]
[pkrvmbietmlfzoi:61848] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e0764527e]
[pkrvmbietmlfzoi:61848] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e076288ff]
[pkrvmbietmlfzoi:61848] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e07aa5ff5]
[pkrvmbietmlfzoi:61848] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e07abb0da]
[pkrvmbietmlfzoi:61848] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e07aa5a55]
[pkrvmbietmlfzoi:61848] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e07aa5a6f]
[pkrvmbietmlfzoi:61848] [ 8] plumed_master(+0x146dd)[0x55ed635ba6dd]
[pkrvmbietmlfzoi:61848] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e0762a1ca]
[pkrvmbietmlfzoi:61848] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e0762a28b]
[pkrvmbietmlfzoi:61848] [11] plumed_master(+0x15365)[0x55ed635bb365]
[pkrvmbietmlfzoi:61848] *** End of error message ***
</pre>
{% endraw %}
