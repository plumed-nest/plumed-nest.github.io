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
[fv-az1391-351:65950] *** Process received signal ***
[fv-az1391-351:65950] Signal: Aborted (6)
[fv-az1391-351:65950] Signal code:  (-6)
[fv-az1391-351:65950] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f20d0e45330]
[fv-az1391-351:65950] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f20d0e9eb2c]
[fv-az1391-351:65950] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f20d0e4527e]
[fv-az1391-351:65950] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f20d0e288ff]
[fv-az1391-351:65950] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f20d12a5ff5]
[fv-az1391-351:65950] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f20d12bb0da]
[fv-az1391-351:65950] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f20d12a5a55]
[fv-az1391-351:65950] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f20d12a5a6f]
[fv-az1391-351:65950] [ 8] plumed_master(+0x146dd)[0x56529d8db6dd]
[fv-az1391-351:65950] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f20d0e2a1ca]
[fv-az1391-351:65950] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f20d0e2a28b]
[fv-az1391-351:65950] [11] plumed_master(+0x15365)[0x56529d8dc365]
[fv-az1391-351:65950] *** End of error message ***
</pre>
{% endraw %}
