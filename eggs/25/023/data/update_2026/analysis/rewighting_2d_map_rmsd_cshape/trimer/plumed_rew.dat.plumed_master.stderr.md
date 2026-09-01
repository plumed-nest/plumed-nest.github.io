**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/trimer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s24 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:05122] *** Process received signal ***
[runnervmgx7h7:05122] Signal: Aborted (6)
[runnervmgx7h7:05122] Signal code:  (-6)
[runnervmgx7h7:05122] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feb37a45330]
[runnervmgx7h7:05122] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feb37a9ec0c]
[runnervmgx7h7:05122] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feb37a4527e]
[runnervmgx7h7:05122] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feb37a288ff]
[runnervmgx7h7:05122] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feb37ea5ff5]
[runnervmgx7h7:05122] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feb37ebb0da]
[runnervmgx7h7:05122] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feb37ea5a55]
[runnervmgx7h7:05122] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feb37ea5a6f]
[runnervmgx7h7:05122] [ 8] plumed_master(+0x146dd)[0x55e12ffda6dd]
[runnervmgx7h7:05122] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feb37a2a1ca]
[runnervmgx7h7:05122] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feb37a2a28b]
[runnervmgx7h7:05122] [11] plumed_master(+0x15365)[0x55e12ffdb365]
[runnervmgx7h7:05122] *** End of error message ***
</pre>
{% endraw %}
