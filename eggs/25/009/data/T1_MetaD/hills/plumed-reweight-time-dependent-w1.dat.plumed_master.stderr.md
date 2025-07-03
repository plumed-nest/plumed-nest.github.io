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
[pkrvmbietmlfzoi:05533] *** Process received signal ***
[pkrvmbietmlfzoi:05533] Signal: Aborted (6)
[pkrvmbietmlfzoi:05533] Signal code:  (-6)
[pkrvmbietmlfzoi:05533] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2748845330]
[pkrvmbietmlfzoi:05533] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f274889eb2c]
[pkrvmbietmlfzoi:05533] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f274884527e]
[pkrvmbietmlfzoi:05533] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f27488288ff]
[pkrvmbietmlfzoi:05533] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2748ca5ff5]
[pkrvmbietmlfzoi:05533] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2748cbb0da]
[pkrvmbietmlfzoi:05533] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2748ca5a55]
[pkrvmbietmlfzoi:05533] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2748ca5a6f]
[pkrvmbietmlfzoi:05533] [ 8] plumed_master(+0x146dd)[0x55b7a6af36dd]
[pkrvmbietmlfzoi:05533] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f274882a1ca]
[pkrvmbietmlfzoi:05533] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f274882a28b]
[pkrvmbietmlfzoi:05533] [11] plumed_master(+0x15365)[0x55b7a6af4365]
[pkrvmbietmlfzoi:05533] *** End of error message ***
</pre>
{% endraw %}
