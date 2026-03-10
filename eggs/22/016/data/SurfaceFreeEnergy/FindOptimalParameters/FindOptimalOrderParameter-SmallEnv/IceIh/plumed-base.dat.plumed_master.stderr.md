**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervm0kj6c:06978] *** Process received signal ***
[runnervm0kj6c:06978] Signal: Aborted (6)
[runnervm0kj6c:06978] Signal code:  (-6)
[runnervm0kj6c:06978] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7febafe45330]
[runnervm0kj6c:06978] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7febafe9eb2c]
[runnervm0kj6c:06978] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7febafe4527e]
[runnervm0kj6c:06978] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7febafe288ff]
[runnervm0kj6c:06978] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7febb02a5ff5]
[runnervm0kj6c:06978] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7febb02bb0da]
[runnervm0kj6c:06978] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7febb02a5a55]
[runnervm0kj6c:06978] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7febb02a5a6f]
[runnervm0kj6c:06978] [ 8] plumed_master(+0x146dd)[0x55de37eeb6dd]
[runnervm0kj6c:06978] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7febafe2a1ca]
[runnervm0kj6c:06978] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7febafe2a28b]
[runnervm0kj6c:06978] [11] plumed_master(+0x15365)[0x55de37eec365]
[runnervm0kj6c:06978] *** End of error message ***
</pre>
{% endraw %}
