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
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:12152] *** Process received signal ***
[pkrvmberfyhpb9w:12152] Signal: Aborted (6)
[pkrvmberfyhpb9w:12152] Signal code:  (-6)
[pkrvmberfyhpb9w:12152] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc241045330]
[pkrvmberfyhpb9w:12152] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc24109eb2c]
[pkrvmberfyhpb9w:12152] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc24104527e]
[pkrvmberfyhpb9w:12152] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc2410288ff]
[pkrvmberfyhpb9w:12152] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc2414a5ff5]
[pkrvmberfyhpb9w:12152] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc2414bb0da]
[pkrvmberfyhpb9w:12152] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc2414a5a55]
[pkrvmberfyhpb9w:12152] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc2414a5a6f]
[pkrvmberfyhpb9w:12152] [ 8] plumed_master(+0x146dd)[0x564a7c6506dd]
[pkrvmberfyhpb9w:12152] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc24102a1ca]
[pkrvmberfyhpb9w:12152] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc24102a28b]
[pkrvmberfyhpb9w:12152] [11] plumed_master(+0x15365)[0x564a7c651365]
[pkrvmberfyhpb9w:12152] *** End of error message ***
</pre>
{% endraw %}
