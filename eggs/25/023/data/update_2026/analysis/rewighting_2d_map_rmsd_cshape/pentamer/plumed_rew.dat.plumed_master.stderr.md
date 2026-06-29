**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/pentamer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s30 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:04585] *** Process received signal ***
[runnervmmklqx:04585] Signal: Aborted (6)
[runnervmmklqx:04585] Signal code:  (-6)
[runnervmmklqx:04585] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb53e445330]
[runnervmmklqx:04585] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb53e49eb2c]
[runnervmmklqx:04585] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb53e44527e]
[runnervmmklqx:04585] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb53e4288ff]
[runnervmmklqx:04585] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb53e8a5ff5]
[runnervmmklqx:04585] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb53e8bb0da]
[runnervmmklqx:04585] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb53e8a5a55]
[runnervmmklqx:04585] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb53e8a5a6f]
[runnervmmklqx:04585] [ 8] plumed_master(+0x146dd)[0x56164e50b6dd]
[runnervmmklqx:04585] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb53e42a1ca]
[runnervmmklqx:04585] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb53e42a28b]
[runnervmmklqx:04585] [11] plumed_master(+0x15365)[0x56164e50c365]
[runnervmmklqx:04585] *** End of error message ***
</pre>
{% endraw %}
