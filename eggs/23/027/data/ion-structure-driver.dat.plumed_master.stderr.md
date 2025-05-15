**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:07085] *** Process received signal ***
[pkrvmberfyhpb9w:07085] Signal: Aborted (6)
[pkrvmberfyhpb9w:07085] Signal code:  (-6)
[pkrvmberfyhpb9w:07085] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb97ea45330]
[pkrvmberfyhpb9w:07085] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb97ea9eb2c]
[pkrvmberfyhpb9w:07085] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb97ea4527e]
[pkrvmberfyhpb9w:07085] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb97ea288ff]
[pkrvmberfyhpb9w:07085] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb97eea5ff5]
[pkrvmberfyhpb9w:07085] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb97eebb0da]
[pkrvmberfyhpb9w:07085] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb97eea5a55]
[pkrvmberfyhpb9w:07085] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb97eea5a6f]
[pkrvmberfyhpb9w:07085] [ 8] plumed_master(+0x146dd)[0x56538e8a96dd]
[pkrvmberfyhpb9w:07085] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb97ea2a1ca]
[pkrvmberfyhpb9w:07085] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb97ea2a28b]
[pkrvmberfyhpb9w:07085] [11] plumed_master(+0x15365)[0x56538e8aa365]
[pkrvmberfyhpb9w:07085] *** End of error message ***
</pre>
{% endraw %}
