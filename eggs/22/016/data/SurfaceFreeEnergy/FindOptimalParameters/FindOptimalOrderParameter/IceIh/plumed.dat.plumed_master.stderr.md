**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:08805] *** Process received signal ***
[pkrvmberfyhpb9w:08805] Signal: Aborted (6)
[pkrvmberfyhpb9w:08805] Signal code:  (-6)
[pkrvmberfyhpb9w:08805] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3348045330]
[pkrvmberfyhpb9w:08805] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f334809eb2c]
[pkrvmberfyhpb9w:08805] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f334804527e]
[pkrvmberfyhpb9w:08805] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f33480288ff]
[pkrvmberfyhpb9w:08805] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f33484a5ff5]
[pkrvmberfyhpb9w:08805] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f33484bb0da]
[pkrvmberfyhpb9w:08805] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f33484a5a55]
[pkrvmberfyhpb9w:08805] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f33484a5a6f]
[pkrvmberfyhpb9w:08805] [ 8] plumed_master(+0x146dd)[0x561cd0ba86dd]
[pkrvmberfyhpb9w:08805] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f334802a1ca]
[pkrvmberfyhpb9w:08805] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f334802a28b]
[pkrvmberfyhpb9w:08805] [11] plumed_master(+0x15365)[0x561cd0ba9365]
[pkrvmberfyhpb9w:08805] *** End of error message ***
</pre>
{% endraw %}
