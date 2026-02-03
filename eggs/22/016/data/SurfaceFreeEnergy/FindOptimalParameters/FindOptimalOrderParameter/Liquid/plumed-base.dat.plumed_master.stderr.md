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
[runnervmkj6or:08146] *** Process received signal ***
[runnervmkj6or:08146] Signal: Aborted (6)
[runnervmkj6or:08146] Signal code:  (-6)
[runnervmkj6or:08146] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9743a45330]
[runnervmkj6or:08146] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9743a9eb2c]
[runnervmkj6or:08146] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9743a4527e]
[runnervmkj6or:08146] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9743a288ff]
[runnervmkj6or:08146] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9743ea5ff5]
[runnervmkj6or:08146] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9743ebb0da]
[runnervmkj6or:08146] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9743ea5a55]
[runnervmkj6or:08146] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9743ea5a6f]
[runnervmkj6or:08146] [ 8] plumed_master(+0x146dd)[0x563b2ff556dd]
[runnervmkj6or:08146] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9743a2a1ca]
[runnervmkj6or:08146] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9743a2a28b]
[runnervmkj6or:08146] [11] plumed_master(+0x15365)[0x563b2ff56365]
[runnervmkj6or:08146] *** End of error message ***
</pre>
{% endraw %}
