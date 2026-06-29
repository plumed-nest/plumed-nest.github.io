**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/IceIh/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmmklqx:07983] *** Process received signal ***
[runnervmmklqx:07983] Signal: Aborted (6)
[runnervmmklqx:07983] Signal code:  (-6)
[runnervmmklqx:07983] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6344445330]
[runnervmmklqx:07983] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f634449eb2c]
[runnervmmklqx:07983] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f634444527e]
[runnervmmklqx:07983] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f63444288ff]
[runnervmmklqx:07983] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63448a5ff5]
[runnervmmklqx:07983] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63448bb0da]
[runnervmmklqx:07983] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63448a5a55]
[runnervmmklqx:07983] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63448a5a6f]
[runnervmmklqx:07983] [ 8] plumed_master(+0x146dd)[0x564bc49e56dd]
[runnervmmklqx:07983] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f634442a1ca]
[runnervmmklqx:07983] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f634442a28b]
[runnervmmklqx:07983] [11] plumed_master(+0x15365)[0x564bc49e6365]
[runnervmmklqx:07983] *** End of error message ***
</pre>
{% endraw %}
