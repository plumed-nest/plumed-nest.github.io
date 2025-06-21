**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:11215] *** Process received signal ***
[pkrvmxyh4eaekms:11215] Signal: Aborted (6)
[pkrvmxyh4eaekms:11215] Signal code:  (-6)
[pkrvmxyh4eaekms:11215] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f11c3445330]
[pkrvmxyh4eaekms:11215] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f11c349eb2c]
[pkrvmxyh4eaekms:11215] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f11c344527e]
[pkrvmxyh4eaekms:11215] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f11c34288ff]
[pkrvmxyh4eaekms:11215] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f11c38a5ff5]
[pkrvmxyh4eaekms:11215] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f11c38bb0da]
[pkrvmxyh4eaekms:11215] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f11c38a5a55]
[pkrvmxyh4eaekms:11215] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f11c38a5a6f]
[pkrvmxyh4eaekms:11215] [ 8] plumed_master(+0x146dd)[0x55a67eb846dd]
[pkrvmxyh4eaekms:11215] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f11c342a1ca]
[pkrvmxyh4eaekms:11215] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f11c342a28b]
[pkrvmxyh4eaekms:11215] [11] plumed_master(+0x15365)[0x55a67eb85365]
[pkrvmxyh4eaekms:11215] *** End of error message ***
</pre>
{% endraw %}
