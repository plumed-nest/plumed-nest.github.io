**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:07543] *** Process received signal ***
[pkrvmpptgkbjq6m:07543] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07543] Signal code:  (-6)
[pkrvmpptgkbjq6m:07543] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff885045330]
[pkrvmpptgkbjq6m:07543] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff88509eb2c]
[pkrvmpptgkbjq6m:07543] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff88504527e]
[pkrvmpptgkbjq6m:07543] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff8850288ff]
[pkrvmpptgkbjq6m:07543] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff8854a5ff5]
[pkrvmpptgkbjq6m:07543] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff8854bb0da]
[pkrvmpptgkbjq6m:07543] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff8854a5a55]
[pkrvmpptgkbjq6m:07543] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff8854a5a6f]
[pkrvmpptgkbjq6m:07543] [ 8] plumed_master(+0x146dd)[0x56097b84a6dd]
[pkrvmpptgkbjq6m:07543] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff88502a1ca]
[pkrvmpptgkbjq6m:07543] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff88502a28b]
[pkrvmpptgkbjq6m:07543] [11] plumed_master(+0x15365)[0x56097b84b365]
[pkrvmpptgkbjq6m:07543] *** End of error message ***
</pre>
{% endraw %}
