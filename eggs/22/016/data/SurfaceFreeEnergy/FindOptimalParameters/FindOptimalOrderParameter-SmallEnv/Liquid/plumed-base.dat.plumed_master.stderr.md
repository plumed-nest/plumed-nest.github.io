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
[runnervmgx7h7:08413] *** Process received signal ***
[runnervmgx7h7:08413] Signal: Aborted (6)
[runnervmgx7h7:08413] Signal code:  (-6)
[runnervmgx7h7:08413] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3741e45330]
[runnervmgx7h7:08413] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3741e9ec0c]
[runnervmgx7h7:08413] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3741e4527e]
[runnervmgx7h7:08413] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3741e288ff]
[runnervmgx7h7:08413] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f37422a5ff5]
[runnervmgx7h7:08413] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f37422bb0da]
[runnervmgx7h7:08413] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f37422a5a55]
[runnervmgx7h7:08413] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f37422a5a6f]
[runnervmgx7h7:08413] [ 8] plumed_master(+0x146dd)[0x55b642af46dd]
[runnervmgx7h7:08413] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3741e2a1ca]
[runnervmgx7h7:08413] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3741e2a28b]
[runnervmgx7h7:08413] [11] plumed_master(+0x15365)[0x55b642af5365]
[runnervmgx7h7:08413] *** End of error message ***
</pre>
{% endraw %}
