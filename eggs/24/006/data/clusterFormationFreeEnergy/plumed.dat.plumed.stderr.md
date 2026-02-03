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
[runnervmkj6or:05742] *** Process received signal ***
[runnervmkj6or:05742] Signal: Aborted (6)
[runnervmkj6or:05742] Signal code:  (-6)
[runnervmkj6or:05742] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffaac045330]
[runnervmkj6or:05742] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffaac09eb2c]
[runnervmkj6or:05742] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffaac04527e]
[runnervmkj6or:05742] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffaac0288ff]
[runnervmkj6or:05742] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffaac4a5ff5]
[runnervmkj6or:05742] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffaac4bb0da]
[runnervmkj6or:05742] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffaac4a5a55]
[runnervmkj6or:05742] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffaac4a5a6f]
[runnervmkj6or:05742] [ 8] plumed(+0x146dd)[0x555c79f006dd]
[runnervmkj6or:05742] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffaac02a1ca]
[runnervmkj6or:05742] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffaac02a28b]
[runnervmkj6or:05742] [11] plumed(+0x15365)[0x555c79f01365]
[runnervmkj6or:05742] *** End of error message ***
</pre>
{% endraw %}
