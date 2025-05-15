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
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:05454] *** Process received signal ***
[pkrvmberfyhpb9w:05454] Signal: Aborted (6)
[pkrvmberfyhpb9w:05454] Signal code:  (-6)
[pkrvmberfyhpb9w:05454] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f54d7e45330]
[pkrvmberfyhpb9w:05454] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f54d7e9eb2c]
[pkrvmberfyhpb9w:05454] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f54d7e4527e]
[pkrvmberfyhpb9w:05454] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f54d7e288ff]
[pkrvmberfyhpb9w:05454] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f54d82a5ff5]
[pkrvmberfyhpb9w:05454] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f54d82bb0da]
[pkrvmberfyhpb9w:05454] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f54d82a5a55]
[pkrvmberfyhpb9w:05454] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f54d82a5a6f]
[pkrvmberfyhpb9w:05454] [ 8] plumed_master(+0x146dd)[0x5559fc53b6dd]
[pkrvmberfyhpb9w:05454] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f54d7e2a1ca]
[pkrvmberfyhpb9w:05454] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f54d7e2a28b]
[pkrvmberfyhpb9w:05454] [11] plumed_master(+0x15365)[0x5559fc53c365]
[pkrvmberfyhpb9w:05454] *** End of error message ***
</pre>
{% endraw %}
