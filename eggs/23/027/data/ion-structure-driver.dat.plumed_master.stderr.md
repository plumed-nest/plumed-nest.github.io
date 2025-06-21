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
[pkrvmxyh4eaekms:07337] *** Process received signal ***
[pkrvmxyh4eaekms:07337] Signal: Aborted (6)
[pkrvmxyh4eaekms:07337] Signal code:  (-6)
[pkrvmxyh4eaekms:07337] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcc88445330]
[pkrvmxyh4eaekms:07337] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcc8849eb2c]
[pkrvmxyh4eaekms:07337] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcc8844527e]
[pkrvmxyh4eaekms:07337] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcc884288ff]
[pkrvmxyh4eaekms:07337] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcc888a5ff5]
[pkrvmxyh4eaekms:07337] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcc888bb0da]
[pkrvmxyh4eaekms:07337] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcc888a5a55]
[pkrvmxyh4eaekms:07337] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcc888a5a6f]
[pkrvmxyh4eaekms:07337] [ 8] plumed_master(+0x146dd)[0x55d4b8c896dd]
[pkrvmxyh4eaekms:07337] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcc8842a1ca]
[pkrvmxyh4eaekms:07337] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcc8842a28b]
[pkrvmxyh4eaekms:07337] [11] plumed_master(+0x15365)[0x55d4b8c8a365]
[pkrvmxyh4eaekms:07337] *** End of error message ***
</pre>
{% endraw %}
