**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/dimer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s21 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:04464] *** Process received signal ***
[runnervmmklqx:04464] Signal: Aborted (6)
[runnervmmklqx:04464] Signal code:  (-6)
[runnervmmklqx:04464] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff201245330]
[runnervmmklqx:04464] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff20129eb2c]
[runnervmmklqx:04464] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff20124527e]
[runnervmmklqx:04464] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2012288ff]
[runnervmmklqx:04464] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2016a5ff5]
[runnervmmklqx:04464] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2016bb0da]
[runnervmmklqx:04464] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2016a5a55]
[runnervmmklqx:04464] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2016a5a6f]
[runnervmmklqx:04464] [ 8] plumed(+0x146dd)[0x55f2eee866dd]
[runnervmmklqx:04464] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff20122a1ca]
[runnervmmklqx:04464] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff20122a28b]
[runnervmmklqx:04464] [11] plumed(+0x15365)[0x55f2eee87365]
[runnervmmklqx:04464] *** End of error message ***
</pre>
{% endraw %}
