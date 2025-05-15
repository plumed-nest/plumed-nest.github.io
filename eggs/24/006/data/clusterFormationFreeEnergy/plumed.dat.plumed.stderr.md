**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:07717] *** Process received signal ***
[pkrvmberfyhpb9w:07717] Signal: Aborted (6)
[pkrvmberfyhpb9w:07717] Signal code:  (-6)
[pkrvmberfyhpb9w:07717] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff5fc845330]
[pkrvmberfyhpb9w:07717] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff5fc89eb2c]
[pkrvmberfyhpb9w:07717] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff5fc84527e]
[pkrvmberfyhpb9w:07717] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5fc8288ff]
[pkrvmberfyhpb9w:07717] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5fcca5ff5]
[pkrvmberfyhpb9w:07717] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5fccbb0da]
[pkrvmberfyhpb9w:07717] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5fcca5a55]
[pkrvmberfyhpb9w:07717] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5fcca5a6f]
[pkrvmberfyhpb9w:07717] [ 8] plumed(+0x146dd)[0x55c7be7956dd]
[pkrvmberfyhpb9w:07717] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff5fc82a1ca]
[pkrvmberfyhpb9w:07717] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff5fc82a28b]
[pkrvmberfyhpb9w:07717] [11] plumed(+0x15365)[0x55c7be796365]
[pkrvmberfyhpb9w:07717] *** End of error message ***
</pre>
{% endraw %}
