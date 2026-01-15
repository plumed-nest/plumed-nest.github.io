**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[runnervmmtnos:37696] *** Process received signal ***
[runnervmmtnos:37696] Signal: Aborted (6)
[runnervmmtnos:37696] Signal code:  (-6)
[runnervmmtnos:37696] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2be0245330]
[runnervmmtnos:37696] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2be029eb2c]
[runnervmmtnos:37696] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2be024527e]
[runnervmmtnos:37696] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2be02288ff]
[runnervmmtnos:37696] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2be06a5ff5]
[runnervmmtnos:37696] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2be06bb0da]
[runnervmmtnos:37696] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2be06a5a55]
[runnervmmtnos:37696] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2be06a5a6f]
[runnervmmtnos:37696] [ 8] plumed_master(+0x146dd)[0x55b05ab2d6dd]
[runnervmmtnos:37696] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2be022a1ca]
[runnervmmtnos:37696] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2be022a28b]
[runnervmmtnos:37696] [11] plumed_master(+0x15365)[0x55b05ab2e365]
[runnervmmtnos:37696] *** End of error message ***
</pre>
{% endraw %}
