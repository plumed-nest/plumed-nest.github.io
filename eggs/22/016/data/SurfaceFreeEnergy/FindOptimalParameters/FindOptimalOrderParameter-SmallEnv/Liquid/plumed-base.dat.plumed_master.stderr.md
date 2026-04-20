**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmeorf1:07441] *** Process received signal ***
[runnervmeorf1:07441] Signal: Aborted (6)
[runnervmeorf1:07441] Signal code:  (-6)
[runnervmeorf1:07441] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f778e245330]
[runnervmeorf1:07441] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f778e29eb2c]
[runnervmeorf1:07441] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f778e24527e]
[runnervmeorf1:07441] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f778e2288ff]
[runnervmeorf1:07441] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f778e6a5ff5]
[runnervmeorf1:07441] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f778e6bb0da]
[runnervmeorf1:07441] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f778e6a5a55]
[runnervmeorf1:07441] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f778e6a5a6f]
[runnervmeorf1:07441] [ 8] plumed_master(+0x146dd)[0x561c882046dd]
[runnervmeorf1:07441] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f778e22a1ca]
[runnervmeorf1:07441] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f778e22a28b]
[runnervmeorf1:07441] [11] plumed_master(+0x15365)[0x561c88205365]
[runnervmeorf1:07441] *** End of error message ***
</pre>
{% endraw %}
