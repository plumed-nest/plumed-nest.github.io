**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @54 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:08884] *** Process received signal ***
[pkrvmberfyhpb9w:08884] Signal: Aborted (6)
[pkrvmberfyhpb9w:08884] Signal code:  (-6)
[pkrvmberfyhpb9w:08884] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd73e245330]
[pkrvmberfyhpb9w:08884] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd73e29eb2c]
[pkrvmberfyhpb9w:08884] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd73e24527e]
[pkrvmberfyhpb9w:08884] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd73e2288ff]
[pkrvmberfyhpb9w:08884] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd73e6a5ff5]
[pkrvmberfyhpb9w:08884] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd73e6bb0da]
[pkrvmberfyhpb9w:08884] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd73e6a5a55]
[pkrvmberfyhpb9w:08884] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd73e6a5a6f]
[pkrvmberfyhpb9w:08884] [ 8] plumed_master(+0x146dd)[0x55987732f6dd]
[pkrvmberfyhpb9w:08884] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd73e22a1ca]
[pkrvmberfyhpb9w:08884] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd73e22a28b]
[pkrvmberfyhpb9w:08884] [11] plumed_master(+0x15365)[0x559877330365]
[pkrvmberfyhpb9w:08884] *** End of error message ***
</pre>
{% endraw %}
