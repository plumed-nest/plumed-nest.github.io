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
[pkrvmq0rgcvqdmg:08269] *** Process received signal ***
[pkrvmq0rgcvqdmg:08269] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08269] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08269] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0db7045330]
[pkrvmq0rgcvqdmg:08269] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0db709eb2c]
[pkrvmq0rgcvqdmg:08269] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0db704527e]
[pkrvmq0rgcvqdmg:08269] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0db70288ff]
[pkrvmq0rgcvqdmg:08269] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0db74a5ff5]
[pkrvmq0rgcvqdmg:08269] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0db74bb0da]
[pkrvmq0rgcvqdmg:08269] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0db74a5a55]
[pkrvmq0rgcvqdmg:08269] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0db74a5a6f]
[pkrvmq0rgcvqdmg:08269] [ 8] plumed_master(+0x146dd)[0x55c9868a76dd]
[pkrvmq0rgcvqdmg:08269] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0db702a1ca]
[pkrvmq0rgcvqdmg:08269] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0db702a28b]
[pkrvmq0rgcvqdmg:08269] [11] plumed_master(+0x15365)[0x55c9868a8365]
[pkrvmq0rgcvqdmg:08269] *** End of error message ***
</pre>
{% endraw %}
