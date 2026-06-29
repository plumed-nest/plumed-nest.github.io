**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/clusters.plmd   
Download: [zipped raw stdout](clusters.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](clusters.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0 : keyword ARG is compulsory for this action
[runnervmmklqx:09654] *** Process received signal ***
[runnervmmklqx:09654] Signal: Aborted (6)
[runnervmmklqx:09654] Signal code:  (-6)
[runnervmmklqx:09654] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef43a45330]
[runnervmmklqx:09654] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef43a9eb2c]
[runnervmmklqx:09654] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef43a4527e]
[runnervmmklqx:09654] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef43a288ff]
[runnervmmklqx:09654] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef43ea5ff5]
[runnervmmklqx:09654] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef43ebb0da]
[runnervmmklqx:09654] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef43ea5a55]
[runnervmmklqx:09654] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef43ea5a6f]
[runnervmmklqx:09654] [ 8] plumed_master(+0x146dd)[0x5599787126dd]
[runnervmmklqx:09654] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef43a2a1ca]
[runnervmmklqx:09654] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef43a2a28b]
[runnervmmklqx:09654] [11] plumed_master(+0x15365)[0x559978713365]
[runnervmmklqx:09654] *** End of error message ***
</pre>
{% endraw %}
