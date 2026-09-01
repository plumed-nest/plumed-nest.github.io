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
[runnervmgx7h7:11726] *** Process received signal ***
[runnervmgx7h7:11726] Signal: Aborted (6)
[runnervmgx7h7:11726] Signal code:  (-6)
[runnervmgx7h7:11726] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faf40a45330]
[runnervmgx7h7:11726] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faf40a9ec0c]
[runnervmgx7h7:11726] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faf40a4527e]
[runnervmgx7h7:11726] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faf40a288ff]
[runnervmgx7h7:11726] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faf40ea5ff5]
[runnervmgx7h7:11726] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faf40ebb0da]
[runnervmgx7h7:11726] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faf40ea5a55]
[runnervmgx7h7:11726] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faf40ea5a6f]
[runnervmgx7h7:11726] [ 8] plumed_master(+0x146dd)[0x5559f5f5b6dd]
[runnervmgx7h7:11726] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faf40a2a1ca]
[runnervmgx7h7:11726] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faf40a2a28b]
[runnervmgx7h7:11726] [11] plumed_master(+0x15365)[0x5559f5f5c365]
[runnervmgx7h7:11726] *** End of error message ***
</pre>
{% endraw %}
