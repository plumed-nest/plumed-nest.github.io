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
[runnervmkj6or:08645] *** Process received signal ***
[runnervmkj6or:08645] Signal: Aborted (6)
[runnervmkj6or:08645] Signal code:  (-6)
[runnervmkj6or:08645] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fde09a45330]
[runnervmkj6or:08645] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fde09a9eb2c]
[runnervmkj6or:08645] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fde09a4527e]
[runnervmkj6or:08645] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fde09a288ff]
[runnervmkj6or:08645] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fde09ea5ff5]
[runnervmkj6or:08645] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fde09ebb0da]
[runnervmkj6or:08645] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fde09ea5a55]
[runnervmkj6or:08645] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fde09ea5a6f]
[runnervmkj6or:08645] [ 8] plumed_master(+0x146dd)[0x555e89c936dd]
[runnervmkj6or:08645] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fde09a2a1ca]
[runnervmkj6or:08645] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fde09a2a28b]
[runnervmkj6or:08645] [11] plumed_master(+0x15365)[0x555e89c94365]
[runnervmkj6or:08645] *** End of error message ***
</pre>
{% endraw %}
