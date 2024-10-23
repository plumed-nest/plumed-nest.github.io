**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/clusters.plmd   
Download: [zipped raw stdout](clusters.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](clusters.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DFSCLUSTERING with label dfs0 : keyword ARG is compulsory for this action
[fv-az585-767:07756] *** Process received signal ***
[fv-az585-767:07756] Signal: Aborted (6)
[fv-az585-767:07756] Signal code:  (-6)
[fv-az585-767:07756] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff1b4042520]
[fv-az585-767:07756] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff1b40969fc]
[fv-az585-767:07756] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff1b4042476]
[fv-az585-767:07756] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff1b40287f3]
[fv-az585-767:07756] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff1b44a2b9e]
[fv-az585-767:07756] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff1b44ae20c]
[fv-az585-767:07756] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff1b44ae277]
[fv-az585-767:07756] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff1b44ae52b]
[fv-az585-767:07756] [ 8] plumed_master(+0x14254)[0x5652cc793254]
[fv-az585-767:07756] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff1b4029d90]
[fv-az585-767:07756] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff1b4029e40]
[fv-az585-767:07756] [11] plumed_master(+0x14eb5)[0x5652cc793eb5]
[fv-az585-767:07756] *** End of error message ***
</pre>
{% endraw %}
