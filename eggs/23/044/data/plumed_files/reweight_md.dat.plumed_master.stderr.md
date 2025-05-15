**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:06309] *** Process received signal ***
[pkrvmberfyhpb9w:06309] Signal: Aborted (6)
[pkrvmberfyhpb9w:06309] Signal code:  (-6)
[pkrvmberfyhpb9w:06309] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fab74a45330]
[pkrvmberfyhpb9w:06309] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fab74a9eb2c]
[pkrvmberfyhpb9w:06309] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fab74a4527e]
[pkrvmberfyhpb9w:06309] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fab74a288ff]
[pkrvmberfyhpb9w:06309] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fab74ea5ff5]
[pkrvmberfyhpb9w:06309] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fab74ebb0da]
[pkrvmberfyhpb9w:06309] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fab74ea5a55]
[pkrvmberfyhpb9w:06309] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fab74ea5a6f]
[pkrvmberfyhpb9w:06309] [ 8] plumed_master(+0x146dd)[0x55aaf21f96dd]
[pkrvmberfyhpb9w:06309] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fab74a2a1ca]
[pkrvmberfyhpb9w:06309] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fab74a2a28b]
[pkrvmberfyhpb9w:06309] [11] plumed_master(+0x15365)[0x55aaf21fa365]
[pkrvmberfyhpb9w:06309] *** End of error message ***
</pre>
{% endraw %}
