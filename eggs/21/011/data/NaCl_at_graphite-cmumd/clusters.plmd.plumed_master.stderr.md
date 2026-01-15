**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/clusters.plmd   
Download: [zipped raw stdout](clusters.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](clusters.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0 : keyword ARG is compulsory for this action
[runnervmmtnos:34670] *** Process received signal ***
[runnervmmtnos:34670] Signal: Aborted (6)
[runnervmmtnos:34670] Signal code:  (-6)
[runnervmmtnos:34670] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9453c45330]
[runnervmmtnos:34670] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9453c9eb2c]
[runnervmmtnos:34670] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9453c4527e]
[runnervmmtnos:34670] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9453c288ff]
[runnervmmtnos:34670] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f94540a5ff5]
[runnervmmtnos:34670] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f94540bb0da]
[runnervmmtnos:34670] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f94540a5a55]
[runnervmmtnos:34670] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f94540a5a6f]
[runnervmmtnos:34670] [ 8] plumed_master(+0x146dd)[0x55f38c3d56dd]
[runnervmmtnos:34670] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9453c2a1ca]
[runnervmmtnos:34670] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9453c2a28b]
[runnervmmtnos:34670] [11] plumed_master(+0x15365)[0x55f38c3d6365]
[runnervmmtnos:34670] *** End of error message ***
</pre>
{% endraw %}
