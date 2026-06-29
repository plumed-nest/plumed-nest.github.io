**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[runnervmmklqx:07081] *** Process received signal ***
[runnervmmklqx:07081] Signal: Aborted (6)
[runnervmmklqx:07081] Signal code:  (-6)
[runnervmmklqx:07081] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8384245330]
[runnervmmklqx:07081] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f838429eb2c]
[runnervmmklqx:07081] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f838424527e]
[runnervmmklqx:07081] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83842288ff]
[runnervmmklqx:07081] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83846a5ff5]
[runnervmmklqx:07081] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83846bb0da]
[runnervmmklqx:07081] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83846a5a55]
[runnervmmklqx:07081] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83846a5a6f]
[runnervmmklqx:07081] [ 8] plumed_master(+0x146dd)[0x555f8727c6dd]
[runnervmmklqx:07081] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f838422a1ca]
[runnervmmklqx:07081] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f838422a28b]
[runnervmmklqx:07081] [11] plumed_master(+0x15365)[0x555f8727d365]
[runnervmmklqx:07081] *** End of error message ***
</pre>
{% endraw %}
