**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[runnervmgx7h7:07021] *** Process received signal ***
[runnervmgx7h7:07021] Signal: Aborted (6)
[runnervmgx7h7:07021] Signal code:  (-6)
[runnervmgx7h7:07021] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f47e6445330]
[runnervmgx7h7:07021] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f47e649ec0c]
[runnervmgx7h7:07021] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f47e644527e]
[runnervmgx7h7:07021] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f47e64288ff]
[runnervmgx7h7:07021] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f47e68a5ff5]
[runnervmgx7h7:07021] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f47e68bb0da]
[runnervmgx7h7:07021] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f47e68a5a55]
[runnervmgx7h7:07021] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f47e68a5a6f]
[runnervmgx7h7:07021] [ 8] plumed(+0x146dd)[0x55749f6cb6dd]
[runnervmgx7h7:07021] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f47e642a1ca]
[runnervmgx7h7:07021] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f47e642a28b]
[runnervmgx7h7:07021] [11] plumed(+0x15365)[0x55749f6cc365]
[runnervmgx7h7:07021] *** End of error message ***
</pre>
{% endraw %}
