**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:08923] *** Process received signal ***
[pkrvmberfyhpb9w:08923] Signal: Aborted (6)
[pkrvmberfyhpb9w:08923] Signal code:  (-6)
[pkrvmberfyhpb9w:08923] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb05ea45330]
[pkrvmberfyhpb9w:08923] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb05ea9eb2c]
[pkrvmberfyhpb9w:08923] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb05ea4527e]
[pkrvmberfyhpb9w:08923] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb05ea288ff]
[pkrvmberfyhpb9w:08923] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb05eea5ff5]
[pkrvmberfyhpb9w:08923] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb05eebb0da]
[pkrvmberfyhpb9w:08923] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb05eea5a55]
[pkrvmberfyhpb9w:08923] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb05eea5a6f]
[pkrvmberfyhpb9w:08923] [ 8] plumed_master(+0x146dd)[0x5640dac2a6dd]
[pkrvmberfyhpb9w:08923] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb05ea2a1ca]
[pkrvmberfyhpb9w:08923] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb05ea2a28b]
[pkrvmberfyhpb9w:08923] [11] plumed_master(+0x15365)[0x5640dac2b365]
[pkrvmberfyhpb9w:08923] *** End of error message ***
</pre>
{% endraw %}
