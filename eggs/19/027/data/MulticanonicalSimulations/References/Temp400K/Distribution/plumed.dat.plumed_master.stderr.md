**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp400K/Distribution/plumed.dat   
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
[pkrvmberfyhpb9w:13845] *** Process received signal ***
[pkrvmberfyhpb9w:13845] Signal: Aborted (6)
[pkrvmberfyhpb9w:13845] Signal code:  (-6)
[pkrvmberfyhpb9w:13845] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd9be445330]
[pkrvmberfyhpb9w:13845] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd9be49eb2c]
[pkrvmberfyhpb9w:13845] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd9be44527e]
[pkrvmberfyhpb9w:13845] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd9be4288ff]
[pkrvmberfyhpb9w:13845] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd9be8a5ff5]
[pkrvmberfyhpb9w:13845] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd9be8bb0da]
[pkrvmberfyhpb9w:13845] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd9be8a5a55]
[pkrvmberfyhpb9w:13845] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd9be8a5a6f]
[pkrvmberfyhpb9w:13845] [ 8] plumed_master(+0x146dd)[0x562571fb36dd]
[pkrvmberfyhpb9w:13845] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd9be42a1ca]
[pkrvmberfyhpb9w:13845] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd9be42a28b]
[pkrvmberfyhpb9w:13845] [11] plumed_master(+0x15365)[0x562571fb4365]
[pkrvmberfyhpb9w:13845] *** End of error message ***
</pre>
{% endraw %}
