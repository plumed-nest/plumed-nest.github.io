**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp600K/Distribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @28 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:14101] *** Process received signal ***
[pkrvmberfyhpb9w:14101] Signal: Aborted (6)
[pkrvmberfyhpb9w:14101] Signal code:  (-6)
[pkrvmberfyhpb9w:14101] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0de1245330]
[pkrvmberfyhpb9w:14101] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0de129eb2c]
[pkrvmberfyhpb9w:14101] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0de124527e]
[pkrvmberfyhpb9w:14101] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0de12288ff]
[pkrvmberfyhpb9w:14101] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0de16a5ff5]
[pkrvmberfyhpb9w:14101] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0de16bb0da]
[pkrvmberfyhpb9w:14101] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0de16a5a55]
[pkrvmberfyhpb9w:14101] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0de16a5a6f]
[pkrvmberfyhpb9w:14101] [ 8] plumed_master(+0x146dd)[0x563c35a326dd]
[pkrvmberfyhpb9w:14101] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0de122a1ca]
[pkrvmberfyhpb9w:14101] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0de122a28b]
[pkrvmberfyhpb9w:14101] [11] plumed_master(+0x15365)[0x563c35a33365]
[pkrvmberfyhpb9w:14101] *** End of error message ***
</pre>
{% endraw %}
