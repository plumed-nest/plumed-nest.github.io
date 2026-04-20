**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed-base.dat   
Download: [zipped raw stdout](plumed-base.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-base.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmeorf1:07288] *** Process received signal ***
[runnervmeorf1:07288] Signal: Aborted (6)
[runnervmeorf1:07288] Signal code:  (-6)
[runnervmeorf1:07288] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2c77045330]
[runnervmeorf1:07288] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2c7709eb2c]
[runnervmeorf1:07288] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2c7704527e]
[runnervmeorf1:07288] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2c770288ff]
[runnervmeorf1:07288] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2c774a5ff5]
[runnervmeorf1:07288] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2c774bb0da]
[runnervmeorf1:07288] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2c774a5a55]
[runnervmeorf1:07288] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2c774a5a6f]
[runnervmeorf1:07288] [ 8] plumed_master(+0x146dd)[0x55d467b1c6dd]
[runnervmeorf1:07288] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2c7702a1ca]
[runnervmeorf1:07288] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2c7702a28b]
[runnervmeorf1:07288] [11] plumed_master(+0x15365)[0x55d467b1d365]
[runnervmeorf1:07288] *** End of error message ***
</pre>
{% endraw %}
