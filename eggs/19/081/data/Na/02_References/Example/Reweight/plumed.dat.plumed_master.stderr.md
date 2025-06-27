**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:67561] *** Process received signal ***
[pkrvmbietmlfzoi:67561] Signal: Aborted (6)
[pkrvmbietmlfzoi:67561] Signal code:  (-6)
[pkrvmbietmlfzoi:67561] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2445445330]
[pkrvmbietmlfzoi:67561] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f244549eb2c]
[pkrvmbietmlfzoi:67561] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f244544527e]
[pkrvmbietmlfzoi:67561] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24454288ff]
[pkrvmbietmlfzoi:67561] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24458a5ff5]
[pkrvmbietmlfzoi:67561] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24458bb0da]
[pkrvmbietmlfzoi:67561] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24458a5a55]
[pkrvmbietmlfzoi:67561] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24458a5a6f]
[pkrvmbietmlfzoi:67561] [ 8] plumed_master(+0x146dd)[0x55c3149cd6dd]
[pkrvmbietmlfzoi:67561] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f244542a1ca]
[pkrvmbietmlfzoi:67561] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f244542a28b]
[pkrvmbietmlfzoi:67561] [11] plumed_master(+0x15365)[0x55c3149ce365]
[pkrvmbietmlfzoi:67561] *** End of error message ***
</pre>
{% endraw %}
