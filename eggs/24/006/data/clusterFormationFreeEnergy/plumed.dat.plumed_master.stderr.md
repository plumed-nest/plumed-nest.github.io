**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[runnervmmtnos:32234] *** Process received signal ***
[runnervmmtnos:32234] Signal: Aborted (6)
[runnervmmtnos:32234] Signal code:  (-6)
[runnervmmtnos:32234] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2775245330]
[runnervmmtnos:32234] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f277529eb2c]
[runnervmmtnos:32234] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f277524527e]
[runnervmmtnos:32234] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f27752288ff]
[runnervmmtnos:32234] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f27756a5ff5]
[runnervmmtnos:32234] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f27756bb0da]
[runnervmmtnos:32234] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f27756a5a55]
[runnervmmtnos:32234] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f27756a5a6f]
[runnervmmtnos:32234] [ 8] plumed_master(+0x146dd)[0x5576cc0266dd]
[runnervmmtnos:32234] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f277522a1ca]
[runnervmmtnos:32234] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f277522a28b]
[runnervmmtnos:32234] [11] plumed_master(+0x15365)[0x5576cc027365]
[runnervmmtnos:32234] *** End of error message ***
</pre>
{% endraw %}
