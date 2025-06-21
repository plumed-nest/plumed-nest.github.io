**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:11330] *** Process received signal ***
[pkrvmxyh4eaekms:11330] Signal: Aborted (6)
[pkrvmxyh4eaekms:11330] Signal code:  (-6)
[pkrvmxyh4eaekms:11330] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb68c845330]
[pkrvmxyh4eaekms:11330] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb68c89eb2c]
[pkrvmxyh4eaekms:11330] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb68c84527e]
[pkrvmxyh4eaekms:11330] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb68c8288ff]
[pkrvmxyh4eaekms:11330] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb68cca5ff5]
[pkrvmxyh4eaekms:11330] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb68ccbb0da]
[pkrvmxyh4eaekms:11330] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb68cca5a55]
[pkrvmxyh4eaekms:11330] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb68cca5a6f]
[pkrvmxyh4eaekms:11330] [ 8] plumed_master(+0x146dd)[0x55e2d38a06dd]
[pkrvmxyh4eaekms:11330] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb68c82a1ca]
[pkrvmxyh4eaekms:11330] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb68c82a28b]
[pkrvmxyh4eaekms:11330] [11] plumed_master(+0x15365)[0x55e2d38a1365]
[pkrvmxyh4eaekms:11330] *** End of error message ***
</pre>
{% endraw %}
