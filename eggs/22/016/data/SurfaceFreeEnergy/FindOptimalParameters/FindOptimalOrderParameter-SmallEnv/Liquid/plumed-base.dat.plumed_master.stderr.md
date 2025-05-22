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
ERROR in input to action DUMPGRID with label @58 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:35186] *** Process received signal ***
[pkrvmf6wy0o8zjz:35186] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:35186] Signal code:  (-6)
[pkrvmf6wy0o8zjz:35186] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f9da45330]
[pkrvmf6wy0o8zjz:35186] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f9da9eb2c]
[pkrvmf6wy0o8zjz:35186] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f9da4527e]
[pkrvmf6wy0o8zjz:35186] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f9da288ff]
[pkrvmf6wy0o8zjz:35186] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f9dea5ff5]
[pkrvmf6wy0o8zjz:35186] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f9debb0da]
[pkrvmf6wy0o8zjz:35186] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f9dea5a55]
[pkrvmf6wy0o8zjz:35186] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f9dea5a6f]
[pkrvmf6wy0o8zjz:35186] [ 8] plumed_master(+0x146dd)[0x56253e0bc6dd]
[pkrvmf6wy0o8zjz:35186] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f9da2a1ca]
[pkrvmf6wy0o8zjz:35186] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f9da2a28b]
[pkrvmf6wy0o8zjz:35186] [11] plumed_master(+0x15365)[0x56253e0bd365]
[pkrvmf6wy0o8zjz:35186] *** End of error message ***
</pre>
{% endraw %}
