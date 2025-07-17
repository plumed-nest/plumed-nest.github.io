**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @55 : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:08035] *** Process received signal ***
[pkrvmq0rgcvqdmg:08035] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08035] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08035] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f425be45330]
[pkrvmq0rgcvqdmg:08035] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f425be9eb2c]
[pkrvmq0rgcvqdmg:08035] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f425be4527e]
[pkrvmq0rgcvqdmg:08035] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f425be288ff]
[pkrvmq0rgcvqdmg:08035] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f425c2a5ff5]
[pkrvmq0rgcvqdmg:08035] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f425c2bb0da]
[pkrvmq0rgcvqdmg:08035] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f425c2a5a55]
[pkrvmq0rgcvqdmg:08035] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f425c2a5a6f]
[pkrvmq0rgcvqdmg:08035] [ 8] plumed_master(+0x146dd)[0x5556903336dd]
[pkrvmq0rgcvqdmg:08035] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f425be2a1ca]
[pkrvmq0rgcvqdmg:08035] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f425be2a28b]
[pkrvmq0rgcvqdmg:08035] [11] plumed_master(+0x15365)[0x555690334365]
[pkrvmq0rgcvqdmg:08035] *** End of error message ***
</pre>
{% endraw %}
