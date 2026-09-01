**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/tetramer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s27 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:05070] *** Process received signal ***
[runnervmgx7h7:05070] Signal: Aborted (6)
[runnervmgx7h7:05070] Signal code:  (-6)
[runnervmgx7h7:05070] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f04d9045330]
[runnervmgx7h7:05070] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f04d909ec0c]
[runnervmgx7h7:05070] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f04d904527e]
[runnervmgx7h7:05070] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f04d90288ff]
[runnervmgx7h7:05070] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f04d94a5ff5]
[runnervmgx7h7:05070] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f04d94bb0da]
[runnervmgx7h7:05070] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f04d94a5a55]
[runnervmgx7h7:05070] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f04d94a5a6f]
[runnervmgx7h7:05070] [ 8] plumed_master(+0x146dd)[0x56120baa56dd]
[runnervmgx7h7:05070] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f04d902a1ca]
[runnervmgx7h7:05070] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f04d902a28b]
[runnervmgx7h7:05070] [11] plumed_master(+0x15365)[0x56120baa6365]
[runnervmgx7h7:05070] *** End of error message ***
</pre>
{% endraw %}
