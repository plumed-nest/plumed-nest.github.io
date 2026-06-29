**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/tetramer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s27 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:04622] *** Process received signal ***
[runnervmmklqx:04622] Signal: Aborted (6)
[runnervmmklqx:04622] Signal code:  (-6)
[runnervmmklqx:04622] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e96c45330]
[runnervmmklqx:04622] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e96c9eb2c]
[runnervmmklqx:04622] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e96c4527e]
[runnervmmklqx:04622] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e96c288ff]
[runnervmmklqx:04622] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e970a5ff5]
[runnervmmklqx:04622] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e970bb0da]
[runnervmmklqx:04622] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e970a5a55]
[runnervmmklqx:04622] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e970a5a6f]
[runnervmmklqx:04622] [ 8] plumed(+0x146dd)[0x558e12ca76dd]
[runnervmmklqx:04622] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e96c2a1ca]
[runnervmmklqx:04622] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e96c2a28b]
[runnervmmklqx:04622] [11] plumed(+0x15365)[0x558e12ca8365]
[runnervmmklqx:04622] *** End of error message ***
</pre>
{% endraw %}
