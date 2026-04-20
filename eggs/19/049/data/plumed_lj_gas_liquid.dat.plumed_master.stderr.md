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
[runnervmeorf1:11182] *** Process received signal ***
[runnervmeorf1:11182] Signal: Aborted (6)
[runnervmeorf1:11182] Signal code:  (-6)
[runnervmeorf1:11182] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3421445330]
[runnervmeorf1:11182] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f342149eb2c]
[runnervmeorf1:11182] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f342144527e]
[runnervmeorf1:11182] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34214288ff]
[runnervmeorf1:11182] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34218a5ff5]
[runnervmeorf1:11182] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34218bb0da]
[runnervmeorf1:11182] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34218a5a55]
[runnervmeorf1:11182] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34218a5a6f]
[runnervmeorf1:11182] [ 8] plumed_master(+0x146dd)[0x55de5aa1d6dd]
[runnervmeorf1:11182] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f342142a1ca]
[runnervmeorf1:11182] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f342142a28b]
[runnervmeorf1:11182] [11] plumed_master(+0x15365)[0x55de5aa1e365]
[runnervmeorf1:11182] *** End of error message ***
</pre>
{% endraw %}
