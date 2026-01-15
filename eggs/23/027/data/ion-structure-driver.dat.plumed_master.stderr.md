**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[runnervmmtnos:32847] *** Process received signal ***
[runnervmmtnos:32847] Signal: Aborted (6)
[runnervmmtnos:32847] Signal code:  (-6)
[runnervmmtnos:32847] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9846a45330]
[runnervmmtnos:32847] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9846a9eb2c]
[runnervmmtnos:32847] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9846a4527e]
[runnervmmtnos:32847] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9846a288ff]
[runnervmmtnos:32847] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9846ea5ff5]
[runnervmmtnos:32847] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9846ebb0da]
[runnervmmtnos:32847] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9846ea5a55]
[runnervmmtnos:32847] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9846ea5a6f]
[runnervmmtnos:32847] [ 8] plumed_master(+0x146dd)[0x555fa27ec6dd]
[runnervmmtnos:32847] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9846a2a1ca]
[runnervmmtnos:32847] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9846a2a28b]
[runnervmmtnos:32847] [11] plumed_master(+0x15365)[0x555fa27ed365]
[runnervmmtnos:32847] *** End of error message ***
</pre>
{% endraw %}
