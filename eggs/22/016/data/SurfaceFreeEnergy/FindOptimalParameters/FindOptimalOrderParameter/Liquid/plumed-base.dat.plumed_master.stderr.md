**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmmklqx:07907] *** Process received signal ***
[runnervmmklqx:07907] Signal: Aborted (6)
[runnervmmklqx:07907] Signal code:  (-6)
[runnervmmklqx:07907] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd046645330]
[runnervmmklqx:07907] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd04669eb2c]
[runnervmmklqx:07907] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd04664527e]
[runnervmmklqx:07907] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd0466288ff]
[runnervmmklqx:07907] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd046aa5ff5]
[runnervmmklqx:07907] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd046abb0da]
[runnervmmklqx:07907] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd046aa5a55]
[runnervmmklqx:07907] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd046aa5a6f]
[runnervmmklqx:07907] [ 8] plumed_master(+0x146dd)[0x5587c59106dd]
[runnervmmklqx:07907] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd04662a1ca]
[runnervmmklqx:07907] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd04662a28b]
[runnervmmklqx:07907] [11] plumed_master(+0x15365)[0x5587c5911365]
[runnervmmklqx:07907] *** End of error message ***
</pre>
{% endraw %}
