**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/clusters.plmd   
Download: [zipped raw stdout](clusters.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](clusters.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:11969] *** Process received signal ***
[pkrvmpptgkbjq6m:11969] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11969] Signal code:  (-6)
[pkrvmpptgkbjq6m:11969] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fce70045330]
[pkrvmpptgkbjq6m:11969] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fce7009eb2c]
[pkrvmpptgkbjq6m:11969] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fce7004527e]
[pkrvmpptgkbjq6m:11969] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fce700288ff]
[pkrvmpptgkbjq6m:11969] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fce704a5ff5]
[pkrvmpptgkbjq6m:11969] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fce704bb0da]
[pkrvmpptgkbjq6m:11969] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fce704a5a55]
[pkrvmpptgkbjq6m:11969] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fce704a5a6f]
[pkrvmpptgkbjq6m:11969] [ 8] plumed_master(+0x146dd)[0x55ca270026dd]
[pkrvmpptgkbjq6m:11969] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fce7002a1ca]
[pkrvmpptgkbjq6m:11969] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fce7002a28b]
[pkrvmpptgkbjq6m:11969] [11] plumed_master(+0x15365)[0x55ca27003365]
[pkrvmpptgkbjq6m:11969] *** End of error message ***
</pre>
{% endraw %}
