**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:11291] *** Process received signal ***
[pkrvmxyh4eaekms:11291] Signal: Aborted (6)
[pkrvmxyh4eaekms:11291] Signal code:  (-6)
[pkrvmxyh4eaekms:11291] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec0b445330]
[pkrvmxyh4eaekms:11291] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec0b49eb2c]
[pkrvmxyh4eaekms:11291] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec0b44527e]
[pkrvmxyh4eaekms:11291] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec0b4288ff]
[pkrvmxyh4eaekms:11291] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec0b8a5ff5]
[pkrvmxyh4eaekms:11291] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec0b8bb0da]
[pkrvmxyh4eaekms:11291] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec0b8a5a55]
[pkrvmxyh4eaekms:11291] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec0b8a5a6f]
[pkrvmxyh4eaekms:11291] [ 8] plumed_master(+0x146dd)[0x560c4e2c86dd]
[pkrvmxyh4eaekms:11291] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec0b42a1ca]
[pkrvmxyh4eaekms:11291] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec0b42a28b]
[pkrvmxyh4eaekms:11291] [11] plumed_master(+0x15365)[0x560c4e2c9365]
[pkrvmxyh4eaekms:11291] *** End of error message ***
</pre>
{% endraw %}
