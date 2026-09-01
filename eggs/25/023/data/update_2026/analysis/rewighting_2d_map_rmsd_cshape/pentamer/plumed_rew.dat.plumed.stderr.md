**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/pentamer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s30 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:05001] *** Process received signal ***
[runnervmgx7h7:05001] Signal: Aborted (6)
[runnervmgx7h7:05001] Signal code:  (-6)
[runnervmgx7h7:05001] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faa10445330]
[runnervmgx7h7:05001] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faa1049ec0c]
[runnervmgx7h7:05001] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faa1044527e]
[runnervmgx7h7:05001] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faa104288ff]
[runnervmgx7h7:05001] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faa108a5ff5]
[runnervmgx7h7:05001] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faa108bb0da]
[runnervmgx7h7:05001] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faa108a5a55]
[runnervmgx7h7:05001] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faa108a5a6f]
[runnervmgx7h7:05001] [ 8] plumed(+0x146dd)[0x55e4e78da6dd]
[runnervmgx7h7:05001] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faa1042a1ca]
[runnervmgx7h7:05001] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faa1042a28b]
[runnervmgx7h7:05001] [11] plumed(+0x15365)[0x55e4e78db365]
[runnervmgx7h7:05001] *** End of error message ***
</pre>
{% endraw %}
