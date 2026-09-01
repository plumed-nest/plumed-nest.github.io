**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[runnervmgx7h7:07037] *** Process received signal ***
[runnervmgx7h7:07037] Signal: Aborted (6)
[runnervmgx7h7:07037] Signal code:  (-6)
[runnervmgx7h7:07037] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7aa9845330]
[runnervmgx7h7:07037] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7aa989ec0c]
[runnervmgx7h7:07037] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7aa984527e]
[runnervmgx7h7:07037] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7aa98288ff]
[runnervmgx7h7:07037] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7aa9ca5ff5]
[runnervmgx7h7:07037] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7aa9cbb0da]
[runnervmgx7h7:07037] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7aa9ca5a55]
[runnervmgx7h7:07037] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7aa9ca5a6f]
[runnervmgx7h7:07037] [ 8] plumed_master(+0x146dd)[0x563def89f6dd]
[runnervmgx7h7:07037] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7aa982a1ca]
[runnervmgx7h7:07037] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7aa982a28b]
[runnervmgx7h7:07037] [11] plumed_master(+0x15365)[0x563def8a0365]
[runnervmgx7h7:07037] *** End of error message ***
</pre>
{% endraw %}
