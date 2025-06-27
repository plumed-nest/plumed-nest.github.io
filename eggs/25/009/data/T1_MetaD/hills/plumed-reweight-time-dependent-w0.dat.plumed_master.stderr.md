**Project ID:** [plumID:25.009]({{ '/' | absolute_url }}eggs/25/009/)  
Stderr for source:  T1_MetaD/hills/plumed-reweight-time-dependent-w0.dat   
Download: [zipped raw stdout](plumed-reweight-time-dependent-w0.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-reweight-time-dependent-w0.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:61809] *** Process received signal ***
[pkrvmbietmlfzoi:61809] Signal: Aborted (6)
[pkrvmbietmlfzoi:61809] Signal code:  (-6)
[pkrvmbietmlfzoi:61809] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff18fe45330]
[pkrvmbietmlfzoi:61809] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff18fe9eb2c]
[pkrvmbietmlfzoi:61809] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff18fe4527e]
[pkrvmbietmlfzoi:61809] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff18fe288ff]
[pkrvmbietmlfzoi:61809] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1902a5ff5]
[pkrvmbietmlfzoi:61809] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1902bb0da]
[pkrvmbietmlfzoi:61809] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1902a5a55]
[pkrvmbietmlfzoi:61809] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1902a5a6f]
[pkrvmbietmlfzoi:61809] [ 8] plumed_master(+0x146dd)[0x55e48fa5b6dd]
[pkrvmbietmlfzoi:61809] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff18fe2a1ca]
[pkrvmbietmlfzoi:61809] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff18fe2a28b]
[pkrvmbietmlfzoi:61809] [11] plumed_master(+0x15365)[0x55e48fa5c365]
[pkrvmbietmlfzoi:61809] *** End of error message ***
</pre>
{% endraw %}
