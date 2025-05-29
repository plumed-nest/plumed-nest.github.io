**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:69984] *** Process received signal ***
[pkrvmf6wy0o8zjz:69984] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69984] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69984] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd792245330]
[pkrvmf6wy0o8zjz:69984] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd79229eb2c]
[pkrvmf6wy0o8zjz:69984] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd79224527e]
[pkrvmf6wy0o8zjz:69984] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7922288ff]
[pkrvmf6wy0o8zjz:69984] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7926a5ff5]
[pkrvmf6wy0o8zjz:69984] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7926bb0da]
[pkrvmf6wy0o8zjz:69984] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7926a5a55]
[pkrvmf6wy0o8zjz:69984] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7926a5a6f]
[pkrvmf6wy0o8zjz:69984] [ 8] plumed_master(+0x146dd)[0x55aecf2c16dd]
[pkrvmf6wy0o8zjz:69984] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd79222a1ca]
[pkrvmf6wy0o8zjz:69984] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd79222a28b]
[pkrvmf6wy0o8zjz:69984] [11] plumed_master(+0x15365)[0x55aecf2c2365]
[pkrvmf6wy0o8zjz:69984] *** End of error message ***
</pre>
{% endraw %}
