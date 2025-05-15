**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:11680] *** Process received signal ***
[pkrvmberfyhpb9w:11680] Signal: Aborted (6)
[pkrvmberfyhpb9w:11680] Signal code:  (-6)
[pkrvmberfyhpb9w:11680] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f042b845330]
[pkrvmberfyhpb9w:11680] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f042b89eb2c]
[pkrvmberfyhpb9w:11680] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f042b84527e]
[pkrvmberfyhpb9w:11680] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f042b8288ff]
[pkrvmberfyhpb9w:11680] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f042bca5ff5]
[pkrvmberfyhpb9w:11680] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f042bcbb0da]
[pkrvmberfyhpb9w:11680] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f042bca5a55]
[pkrvmberfyhpb9w:11680] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f042bca5a6f]
[pkrvmberfyhpb9w:11680] [ 8] plumed_master(+0x146dd)[0x5578feef06dd]
[pkrvmberfyhpb9w:11680] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f042b82a1ca]
[pkrvmberfyhpb9w:11680] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f042b82a28b]
[pkrvmberfyhpb9w:11680] [11] plumed_master(+0x15365)[0x5578feef1365]
[pkrvmberfyhpb9w:11680] *** End of error message ***
</pre>
{% endraw %}
