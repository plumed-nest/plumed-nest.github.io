**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:07734] *** Process received signal ***
[pkrvmberfyhpb9w:07734] Signal: Aborted (6)
[pkrvmberfyhpb9w:07734] Signal code:  (-6)
[pkrvmberfyhpb9w:07734] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4c58a45330]
[pkrvmberfyhpb9w:07734] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4c58a9eb2c]
[pkrvmberfyhpb9w:07734] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4c58a4527e]
[pkrvmberfyhpb9w:07734] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4c58a288ff]
[pkrvmberfyhpb9w:07734] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4c58ea5ff5]
[pkrvmberfyhpb9w:07734] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4c58ebb0da]
[pkrvmberfyhpb9w:07734] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4c58ea5a55]
[pkrvmberfyhpb9w:07734] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4c58ea5a6f]
[pkrvmberfyhpb9w:07734] [ 8] plumed_master(+0x146dd)[0x55b16bb7f6dd]
[pkrvmberfyhpb9w:07734] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4c58a2a1ca]
[pkrvmberfyhpb9w:07734] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4c58a2a28b]
[pkrvmberfyhpb9w:07734] [11] plumed_master(+0x15365)[0x55b16bb80365]
[pkrvmberfyhpb9w:07734] *** End of error message ***
</pre>
{% endraw %}
