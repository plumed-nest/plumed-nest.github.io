**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:09001] *** Process received signal ***
[pkrvmberfyhpb9w:09001] Signal: Aborted (6)
[pkrvmberfyhpb9w:09001] Signal code:  (-6)
[pkrvmberfyhpb9w:09001] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f64a5045330]
[pkrvmberfyhpb9w:09001] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f64a509eb2c]
[pkrvmberfyhpb9w:09001] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f64a504527e]
[pkrvmberfyhpb9w:09001] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f64a50288ff]
[pkrvmberfyhpb9w:09001] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64a54a5ff5]
[pkrvmberfyhpb9w:09001] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64a54bb0da]
[pkrvmberfyhpb9w:09001] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64a54a5a55]
[pkrvmberfyhpb9w:09001] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64a54a5a6f]
[pkrvmberfyhpb9w:09001] [ 8] plumed_master(+0x146dd)[0x55e8bd5816dd]
[pkrvmberfyhpb9w:09001] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f64a502a1ca]
[pkrvmberfyhpb9w:09001] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f64a502a28b]
[pkrvmberfyhpb9w:09001] [11] plumed_master(+0x15365)[0x55e8bd582365]
[pkrvmberfyhpb9w:09001] *** End of error message ***
</pre>
{% endraw %}
