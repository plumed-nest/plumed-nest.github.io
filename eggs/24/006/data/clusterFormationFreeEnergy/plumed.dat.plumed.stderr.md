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
[pkrvmq0rgcvqdmg:07260] *** Process received signal ***
[pkrvmq0rgcvqdmg:07260] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:07260] Signal code:  (-6)
[pkrvmq0rgcvqdmg:07260] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8461a45330]
[pkrvmq0rgcvqdmg:07260] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8461a9eb2c]
[pkrvmq0rgcvqdmg:07260] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8461a4527e]
[pkrvmq0rgcvqdmg:07260] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8461a288ff]
[pkrvmq0rgcvqdmg:07260] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8461ea5ff5]
[pkrvmq0rgcvqdmg:07260] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8461ebb0da]
[pkrvmq0rgcvqdmg:07260] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8461ea5a55]
[pkrvmq0rgcvqdmg:07260] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8461ea5a6f]
[pkrvmq0rgcvqdmg:07260] [ 8] plumed(+0x146dd)[0x5619d2e726dd]
[pkrvmq0rgcvqdmg:07260] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8461a2a1ca]
[pkrvmq0rgcvqdmg:07260] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8461a2a28b]
[pkrvmq0rgcvqdmg:07260] [11] plumed(+0x15365)[0x5619d2e73365]
[pkrvmq0rgcvqdmg:07260] *** End of error message ***
</pre>
{% endraw %}
