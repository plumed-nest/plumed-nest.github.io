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
[runnervmmklqx:06185] *** Process received signal ***
[runnervmmklqx:06185] Signal: Aborted (6)
[runnervmmklqx:06185] Signal code:  (-6)
[runnervmmklqx:06185] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f40f1645330]
[runnervmmklqx:06185] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f40f169eb2c]
[runnervmmklqx:06185] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f40f164527e]
[runnervmmklqx:06185] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f40f16288ff]
[runnervmmklqx:06185] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f40f1aa5ff5]
[runnervmmklqx:06185] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f40f1abb0da]
[runnervmmklqx:06185] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f40f1aa5a55]
[runnervmmklqx:06185] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f40f1aa5a6f]
[runnervmmklqx:06185] [ 8] plumed_master(+0x146dd)[0x5586932716dd]
[runnervmmklqx:06185] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f40f162a1ca]
[runnervmmklqx:06185] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f40f162a28b]
[runnervmmklqx:06185] [11] plumed_master(+0x15365)[0x558693272365]
[runnervmmklqx:06185] *** End of error message ***
</pre>
{% endraw %}
