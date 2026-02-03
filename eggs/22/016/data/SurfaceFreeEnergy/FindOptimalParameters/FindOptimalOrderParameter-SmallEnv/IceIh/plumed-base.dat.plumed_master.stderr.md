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
[runnervmkj6or:08222] *** Process received signal ***
[runnervmkj6or:08222] Signal: Aborted (6)
[runnervmkj6or:08222] Signal code:  (-6)
[runnervmkj6or:08222] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7ba0845330]
[runnervmkj6or:08222] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7ba089eb2c]
[runnervmkj6or:08222] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7ba084527e]
[runnervmkj6or:08222] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7ba08288ff]
[runnervmkj6or:08222] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7ba0ca5ff5]
[runnervmkj6or:08222] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7ba0cbb0da]
[runnervmkj6or:08222] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7ba0ca5a55]
[runnervmkj6or:08222] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7ba0ca5a6f]
[runnervmkj6or:08222] [ 8] plumed_master(+0x146dd)[0x56526396e6dd]
[runnervmkj6or:08222] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7ba082a1ca]
[runnervmkj6or:08222] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7ba082a28b]
[runnervmkj6or:08222] [11] plumed_master(+0x15365)[0x56526396f365]
[runnervmkj6or:08222] *** End of error message ***
</pre>
{% endraw %}
