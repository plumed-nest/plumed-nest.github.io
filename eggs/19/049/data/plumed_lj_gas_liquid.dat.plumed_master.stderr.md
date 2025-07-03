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
[pkrvmbietmlfzoi:10262] *** Process received signal ***
[pkrvmbietmlfzoi:10262] Signal: Aborted (6)
[pkrvmbietmlfzoi:10262] Signal code:  (-6)
[pkrvmbietmlfzoi:10262] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f231b845330]
[pkrvmbietmlfzoi:10262] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f231b89eb2c]
[pkrvmbietmlfzoi:10262] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f231b84527e]
[pkrvmbietmlfzoi:10262] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f231b8288ff]
[pkrvmbietmlfzoi:10262] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f231bca5ff5]
[pkrvmbietmlfzoi:10262] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f231bcbb0da]
[pkrvmbietmlfzoi:10262] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f231bca5a55]
[pkrvmbietmlfzoi:10262] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f231bca5a6f]
[pkrvmbietmlfzoi:10262] [ 8] plumed_master(+0x146dd)[0x56478c1286dd]
[pkrvmbietmlfzoi:10262] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f231b82a1ca]
[pkrvmbietmlfzoi:10262] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f231b82a28b]
[pkrvmbietmlfzoi:10262] [11] plumed_master(+0x15365)[0x56478c129365]
[pkrvmbietmlfzoi:10262] *** End of error message ***
</pre>
{% endraw %}
