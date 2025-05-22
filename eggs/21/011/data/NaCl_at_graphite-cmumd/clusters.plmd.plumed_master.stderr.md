**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/clusters.plmd   
Download: [zipped raw stdout](clusters.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](clusters.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:38045] *** Process received signal ***
[pkrvmf6wy0o8zjz:38045] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38045] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38045] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb4b6645330]
[pkrvmf6wy0o8zjz:38045] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb4b669eb2c]
[pkrvmf6wy0o8zjz:38045] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb4b664527e]
[pkrvmf6wy0o8zjz:38045] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb4b66288ff]
[pkrvmf6wy0o8zjz:38045] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb4b6aa5ff5]
[pkrvmf6wy0o8zjz:38045] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb4b6abb0da]
[pkrvmf6wy0o8zjz:38045] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb4b6aa5a55]
[pkrvmf6wy0o8zjz:38045] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb4b6aa5a6f]
[pkrvmf6wy0o8zjz:38045] [ 8] plumed_master(+0x146dd)[0x5596ef31f6dd]
[pkrvmf6wy0o8zjz:38045] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb4b662a1ca]
[pkrvmf6wy0o8zjz:38045] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb4b662a28b]
[pkrvmf6wy0o8zjz:38045] [11] plumed_master(+0x15365)[0x5596ef320365]
[pkrvmf6wy0o8zjz:38045] *** End of error message ***
</pre>
{% endraw %}
