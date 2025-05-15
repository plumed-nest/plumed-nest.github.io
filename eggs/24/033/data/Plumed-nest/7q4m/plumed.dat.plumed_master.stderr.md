**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[pkrvmberfyhpb9w:05718] *** Process received signal ***
[pkrvmberfyhpb9w:05718] Signal: Aborted (6)
[pkrvmberfyhpb9w:05718] Signal code:  (-6)
[pkrvmberfyhpb9w:05718] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7491a45330]
[pkrvmberfyhpb9w:05718] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7491a9eb2c]
[pkrvmberfyhpb9w:05718] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7491a4527e]
[pkrvmberfyhpb9w:05718] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7491a288ff]
[pkrvmberfyhpb9w:05718] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7491ea5ff5]
[pkrvmberfyhpb9w:05718] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7491ebb0da]
[pkrvmberfyhpb9w:05718] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7491ea5a55]
[pkrvmberfyhpb9w:05718] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7491ea5a6f]
[pkrvmberfyhpb9w:05718] [ 8] plumed_master(+0x146dd)[0x55ecbd6eb6dd]
[pkrvmberfyhpb9w:05718] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7491a2a1ca]
[pkrvmberfyhpb9w:05718] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7491a2a28b]
[pkrvmberfyhpb9w:05718] [11] plumed_master(+0x15365)[0x55ecbd6ec365]
[pkrvmberfyhpb9w:05718] *** End of error message ***
</pre>
{% endraw %}
