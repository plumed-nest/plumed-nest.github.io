**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:35362] *** Process received signal ***
[pkrvmf6wy0o8zjz:35362] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:35362] Signal code:  (-6)
[pkrvmf6wy0o8zjz:35362] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbf68a45330]
[pkrvmf6wy0o8zjz:35362] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbf68a9eb2c]
[pkrvmf6wy0o8zjz:35362] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbf68a4527e]
[pkrvmf6wy0o8zjz:35362] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbf68a288ff]
[pkrvmf6wy0o8zjz:35362] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbf68ea5ff5]
[pkrvmf6wy0o8zjz:35362] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbf68ebb0da]
[pkrvmf6wy0o8zjz:35362] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbf68ea5a55]
[pkrvmf6wy0o8zjz:35362] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbf68ea5a6f]
[pkrvmf6wy0o8zjz:35362] [ 8] plumed_master(+0x146dd)[0x55b3604cb6dd]
[pkrvmf6wy0o8zjz:35362] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbf68a2a1ca]
[pkrvmf6wy0o8zjz:35362] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbf68a2a28b]
[pkrvmf6wy0o8zjz:35362] [11] plumed_master(+0x15365)[0x55b3604cc365]
[pkrvmf6wy0o8zjz:35362] *** End of error message ***
</pre>
{% endraw %}
