**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmmklqx:08060] *** Process received signal ***
[runnervmmklqx:08060] Signal: Aborted (6)
[runnervmmklqx:08060] Signal code:  (-6)
[runnervmmklqx:08060] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4e93c45330]
[runnervmmklqx:08060] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4e93c9eb2c]
[runnervmmklqx:08060] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4e93c4527e]
[runnervmmklqx:08060] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4e93c288ff]
[runnervmmklqx:08060] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4e940a5ff5]
[runnervmmklqx:08060] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4e940bb0da]
[runnervmmklqx:08060] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4e940a5a55]
[runnervmmklqx:08060] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4e940a5a6f]
[runnervmmklqx:08060] [ 8] plumed_master(+0x146dd)[0x56268865f6dd]
[runnervmmklqx:08060] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4e93c2a1ca]
[runnervmmklqx:08060] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4e93c2a28b]
[runnervmmklqx:08060] [11] plumed_master(+0x15365)[0x562688660365]
[runnervmmklqx:08060] *** End of error message ***
</pre>
{% endraw %}
