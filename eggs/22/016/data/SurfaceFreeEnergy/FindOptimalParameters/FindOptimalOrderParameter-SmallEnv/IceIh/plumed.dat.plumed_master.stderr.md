**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:08961] *** Process received signal ***
[pkrvmberfyhpb9w:08961] Signal: Aborted (6)
[pkrvmberfyhpb9w:08961] Signal code:  (-6)
[pkrvmberfyhpb9w:08961] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5fa0845330]
[pkrvmberfyhpb9w:08961] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5fa089eb2c]
[pkrvmberfyhpb9w:08961] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5fa084527e]
[pkrvmberfyhpb9w:08961] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5fa08288ff]
[pkrvmberfyhpb9w:08961] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5fa0ca5ff5]
[pkrvmberfyhpb9w:08961] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5fa0cbb0da]
[pkrvmberfyhpb9w:08961] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5fa0ca5a55]
[pkrvmberfyhpb9w:08961] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5fa0ca5a6f]
[pkrvmberfyhpb9w:08961] [ 8] plumed_master(+0x146dd)[0x55e1a9df86dd]
[pkrvmberfyhpb9w:08961] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5fa082a1ca]
[pkrvmberfyhpb9w:08961] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5fa082a28b]
[pkrvmberfyhpb9w:08961] [11] plumed_master(+0x15365)[0x55e1a9df9365]
[pkrvmberfyhpb9w:08961] *** End of error message ***
</pre>
{% endraw %}
