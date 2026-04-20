**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[runnervmeorf1:07178] *** Process received signal ***
[runnervmeorf1:07178] Signal: Aborted (6)
[runnervmeorf1:07178] Signal code:  (-6)
[runnervmeorf1:07178] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd38da45330]
[runnervmeorf1:07178] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd38da9eb2c]
[runnervmeorf1:07178] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd38da4527e]
[runnervmeorf1:07178] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd38da288ff]
[runnervmeorf1:07178] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd38dea5ff5]
[runnervmeorf1:07178] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd38debb0da]
[runnervmeorf1:07178] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd38dea5a55]
[runnervmeorf1:07178] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd38dea5a6f]
[runnervmeorf1:07178] [ 8] plumed(+0x146dd)[0x55705f3b36dd]
[runnervmeorf1:07178] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd38da2a1ca]
[runnervmeorf1:07178] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd38da2a28b]
[runnervmeorf1:07178] [11] plumed(+0x15365)[0x55705f3b4365]
[runnervmeorf1:07178] *** End of error message ***
</pre>
{% endraw %}
