**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmeorf1:07480] *** Process received signal ***
[runnervmeorf1:07480] Signal: Aborted (6)
[runnervmeorf1:07480] Signal code:  (-6)
[runnervmeorf1:07480] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdb2ea45330]
[runnervmeorf1:07480] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdb2ea9eb2c]
[runnervmeorf1:07480] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdb2ea4527e]
[runnervmeorf1:07480] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdb2ea288ff]
[runnervmeorf1:07480] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdb2eea5ff5]
[runnervmeorf1:07480] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdb2eebb0da]
[runnervmeorf1:07480] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdb2eea5a55]
[runnervmeorf1:07480] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdb2eea5a6f]
[runnervmeorf1:07480] [ 8] plumed_master(+0x146dd)[0x55a04cc736dd]
[runnervmeorf1:07480] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdb2ea2a1ca]
[runnervmeorf1:07480] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdb2ea2a28b]
[runnervmeorf1:07480] [11] plumed_master(+0x15365)[0x55a04cc74365]
[runnervmeorf1:07480] *** End of error message ***
</pre>
{% endraw %}
