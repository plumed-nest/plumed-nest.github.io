**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:09039] *** Process received signal ***
[pkrvmberfyhpb9w:09039] Signal: Aborted (6)
[pkrvmberfyhpb9w:09039] Signal code:  (-6)
[pkrvmberfyhpb9w:09039] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f61ba845330]
[pkrvmberfyhpb9w:09039] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f61ba89eb2c]
[pkrvmberfyhpb9w:09039] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f61ba84527e]
[pkrvmberfyhpb9w:09039] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f61ba8288ff]
[pkrvmberfyhpb9w:09039] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f61baca5ff5]
[pkrvmberfyhpb9w:09039] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f61bacbb0da]
[pkrvmberfyhpb9w:09039] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f61baca5a55]
[pkrvmberfyhpb9w:09039] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f61baca5a6f]
[pkrvmberfyhpb9w:09039] [ 8] plumed_master(+0x146dd)[0x55a22d3e36dd]
[pkrvmberfyhpb9w:09039] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f61ba82a1ca]
[pkrvmberfyhpb9w:09039] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f61ba82a28b]
[pkrvmberfyhpb9w:09039] [11] plumed_master(+0x15365)[0x55a22d3e4365]
[pkrvmberfyhpb9w:09039] *** End of error message ***
</pre>
{% endraw %}
