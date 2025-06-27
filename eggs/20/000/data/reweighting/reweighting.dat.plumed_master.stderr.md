**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:67924] *** Process received signal ***
[pkrvmbietmlfzoi:67924] Signal: Aborted (6)
[pkrvmbietmlfzoi:67924] Signal code:  (-6)
[pkrvmbietmlfzoi:67924] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc6e3445330]
[pkrvmbietmlfzoi:67924] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc6e349eb2c]
[pkrvmbietmlfzoi:67924] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc6e344527e]
[pkrvmbietmlfzoi:67924] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6e34288ff]
[pkrvmbietmlfzoi:67924] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6e38a5ff5]
[pkrvmbietmlfzoi:67924] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6e38bb0da]
[pkrvmbietmlfzoi:67924] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6e38a5a55]
[pkrvmbietmlfzoi:67924] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6e38a5a6f]
[pkrvmbietmlfzoi:67924] [ 8] plumed_master(+0x146dd)[0x55c00470f6dd]
[pkrvmbietmlfzoi:67924] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc6e342a1ca]
[pkrvmbietmlfzoi:67924] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc6e342a28b]
[pkrvmbietmlfzoi:67924] [11] plumed_master(+0x15365)[0x55c004710365]
[pkrvmbietmlfzoi:67924] *** End of error message ***
</pre>
{% endraw %}
