**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/IceIh/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmkj6or:08108] *** Process received signal ***
[runnervmkj6or:08108] Signal: Aborted (6)
[runnervmkj6or:08108] Signal code:  (-6)
[runnervmkj6or:08108] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1a7e245330]
[runnervmkj6or:08108] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1a7e29eb2c]
[runnervmkj6or:08108] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1a7e24527e]
[runnervmkj6or:08108] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1a7e2288ff]
[runnervmkj6or:08108] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1a7e6a5ff5]
[runnervmkj6or:08108] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1a7e6bb0da]
[runnervmkj6or:08108] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1a7e6a5a55]
[runnervmkj6or:08108] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1a7e6a5a6f]
[runnervmkj6or:08108] [ 8] plumed_master(+0x146dd)[0x55b2baa426dd]
[runnervmkj6or:08108] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1a7e22a1ca]
[runnervmkj6or:08108] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1a7e22a28b]
[runnervmkj6or:08108] [11] plumed_master(+0x15365)[0x55b2baa43365]
[runnervmkj6or:08108] *** End of error message ***
</pre>
{% endraw %}
