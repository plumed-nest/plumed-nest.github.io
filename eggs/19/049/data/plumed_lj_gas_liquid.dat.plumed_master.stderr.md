**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[pkrvmxyh4eaekms:14076] *** Process received signal ***
[pkrvmxyh4eaekms:14076] Signal: Aborted (6)
[pkrvmxyh4eaekms:14076] Signal code:  (-6)
[pkrvmxyh4eaekms:14076] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4eb8445330]
[pkrvmxyh4eaekms:14076] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4eb849eb2c]
[pkrvmxyh4eaekms:14076] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4eb844527e]
[pkrvmxyh4eaekms:14076] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4eb84288ff]
[pkrvmxyh4eaekms:14076] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4eb88a5ff5]
[pkrvmxyh4eaekms:14076] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4eb88bb0da]
[pkrvmxyh4eaekms:14076] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4eb88a5a55]
[pkrvmxyh4eaekms:14076] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4eb88a5a6f]
[pkrvmxyh4eaekms:14076] [ 8] plumed_master(+0x146dd)[0x562e236e56dd]
[pkrvmxyh4eaekms:14076] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4eb842a1ca]
[pkrvmxyh4eaekms:14076] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4eb842a28b]
[pkrvmxyh4eaekms:14076] [11] plumed_master(+0x15365)[0x562e236e6365]
[pkrvmxyh4eaekms:14076] *** End of error message ***
</pre>
{% endraw %}
