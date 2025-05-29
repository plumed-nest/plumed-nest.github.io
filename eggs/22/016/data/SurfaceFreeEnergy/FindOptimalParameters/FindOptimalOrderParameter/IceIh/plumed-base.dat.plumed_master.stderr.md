**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:62913] *** Process received signal ***
[pkrvmf6wy0o8zjz:62913] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62913] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62913] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe4e7645330]
[pkrvmf6wy0o8zjz:62913] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe4e769eb2c]
[pkrvmf6wy0o8zjz:62913] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe4e764527e]
[pkrvmf6wy0o8zjz:62913] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe4e76288ff]
[pkrvmf6wy0o8zjz:62913] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe4e7aa5ff5]
[pkrvmf6wy0o8zjz:62913] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe4e7abb0da]
[pkrvmf6wy0o8zjz:62913] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe4e7aa5a55]
[pkrvmf6wy0o8zjz:62913] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe4e7aa5a6f]
[pkrvmf6wy0o8zjz:62913] [ 8] plumed_master(+0x146dd)[0x5628b97076dd]
[pkrvmf6wy0o8zjz:62913] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe4e762a1ca]
[pkrvmf6wy0o8zjz:62913] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe4e762a28b]
[pkrvmf6wy0o8zjz:62913] [11] plumed_master(+0x15365)[0x5628b9708365]
[pkrvmf6wy0o8zjz:62913] *** End of error message ***
</pre>
{% endraw %}
