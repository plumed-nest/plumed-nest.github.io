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
[pkrvmpptgkbjq6m:11103] *** Process received signal ***
[pkrvmpptgkbjq6m:11103] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11103] Signal code:  (-6)
[pkrvmpptgkbjq6m:11103] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f383dc45330]
[pkrvmpptgkbjq6m:11103] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f383dc9eb2c]
[pkrvmpptgkbjq6m:11103] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f383dc4527e]
[pkrvmpptgkbjq6m:11103] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f383dc288ff]
[pkrvmpptgkbjq6m:11103] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f383e0a5ff5]
[pkrvmpptgkbjq6m:11103] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f383e0bb0da]
[pkrvmpptgkbjq6m:11103] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f383e0a5a55]
[pkrvmpptgkbjq6m:11103] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f383e0a5a6f]
[pkrvmpptgkbjq6m:11103] [ 8] plumed_master(+0x146dd)[0x561e7b2426dd]
[pkrvmpptgkbjq6m:11103] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f383dc2a1ca]
[pkrvmpptgkbjq6m:11103] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f383dc2a28b]
[pkrvmpptgkbjq6m:11103] [11] plumed_master(+0x15365)[0x561e7b243365]
[pkrvmpptgkbjq6m:11103] *** End of error message ***
</pre>
{% endraw %}
