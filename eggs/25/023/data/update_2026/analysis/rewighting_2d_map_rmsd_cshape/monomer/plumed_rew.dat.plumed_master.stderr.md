**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/monomer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s16 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:04532] *** Process received signal ***
[runnervmmklqx:04532] Signal: Aborted (6)
[runnervmmklqx:04532] Signal code:  (-6)
[runnervmmklqx:04532] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f377a445330]
[runnervmmklqx:04532] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f377a49eb2c]
[runnervmmklqx:04532] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f377a44527e]
[runnervmmklqx:04532] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f377a4288ff]
[runnervmmklqx:04532] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f377a8a5ff5]
[runnervmmklqx:04532] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f377a8bb0da]
[runnervmmklqx:04532] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f377a8a5a55]
[runnervmmklqx:04532] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f377a8a5a6f]
[runnervmmklqx:04532] [ 8] plumed_master(+0x146dd)[0x55fde39cd6dd]
[runnervmmklqx:04532] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f377a42a1ca]
[runnervmmklqx:04532] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f377a42a28b]
[runnervmmklqx:04532] [11] plumed_master(+0x15365)[0x55fde39ce365]
[runnervmmklqx:04532] *** End of error message ***
</pre>
{% endraw %}
