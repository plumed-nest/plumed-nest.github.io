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
[pkrvmq0rgcvqdmg:08230] *** Process received signal ***
[pkrvmq0rgcvqdmg:08230] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08230] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08230] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f975ec45330]
[pkrvmq0rgcvqdmg:08230] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f975ec9eb2c]
[pkrvmq0rgcvqdmg:08230] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f975ec4527e]
[pkrvmq0rgcvqdmg:08230] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f975ec288ff]
[pkrvmq0rgcvqdmg:08230] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f975f0a5ff5]
[pkrvmq0rgcvqdmg:08230] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f975f0bb0da]
[pkrvmq0rgcvqdmg:08230] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f975f0a5a55]
[pkrvmq0rgcvqdmg:08230] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f975f0a5a6f]
[pkrvmq0rgcvqdmg:08230] [ 8] plumed_master(+0x146dd)[0x5557b98d16dd]
[pkrvmq0rgcvqdmg:08230] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f975ec2a1ca]
[pkrvmq0rgcvqdmg:08230] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f975ec2a28b]
[pkrvmq0rgcvqdmg:08230] [11] plumed_master(+0x15365)[0x5557b98d2365]
[pkrvmq0rgcvqdmg:08230] *** End of error message ***
</pre>
{% endraw %}
