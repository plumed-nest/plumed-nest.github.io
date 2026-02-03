**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmkj6or:08184] *** Process received signal ***
[runnervmkj6or:08184] Signal: Aborted (6)
[runnervmkj6or:08184] Signal code:  (-6)
[runnervmkj6or:08184] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f60e5c45330]
[runnervmkj6or:08184] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f60e5c9eb2c]
[runnervmkj6or:08184] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f60e5c4527e]
[runnervmkj6or:08184] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f60e5c288ff]
[runnervmkj6or:08184] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f60e60a5ff5]
[runnervmkj6or:08184] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f60e60bb0da]
[runnervmkj6or:08184] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f60e60a5a55]
[runnervmkj6or:08184] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f60e60a5a6f]
[runnervmkj6or:08184] [ 8] plumed_master(+0x146dd)[0x55c80568e6dd]
[runnervmkj6or:08184] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f60e5c2a1ca]
[runnervmkj6or:08184] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f60e5c2a28b]
[runnervmkj6or:08184] [11] plumed_master(+0x15365)[0x55c80568f365]
[runnervmkj6or:08184] *** End of error message ***
</pre>
{% endraw %}
