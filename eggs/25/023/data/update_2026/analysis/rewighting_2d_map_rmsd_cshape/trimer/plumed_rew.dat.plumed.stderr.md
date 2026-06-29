**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/trimer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s24 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:04674] *** Process received signal ***
[runnervmmklqx:04674] Signal: Aborted (6)
[runnervmmklqx:04674] Signal code:  (-6)
[runnervmmklqx:04674] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff397c45330]
[runnervmmklqx:04674] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff397c9eb2c]
[runnervmmklqx:04674] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff397c4527e]
[runnervmmklqx:04674] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff397c288ff]
[runnervmmklqx:04674] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff3980a5ff5]
[runnervmmklqx:04674] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff3980bb0da]
[runnervmmklqx:04674] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff3980a5a55]
[runnervmmklqx:04674] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff3980a5a6f]
[runnervmmklqx:04674] [ 8] plumed(+0x146dd)[0x55baaf87f6dd]
[runnervmmklqx:04674] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff397c2a1ca]
[runnervmmklqx:04674] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff397c2a28b]
[runnervmmklqx:04674] [11] plumed(+0x15365)[0x55baaf880365]
[runnervmmklqx:04674] *** End of error message ***
</pre>
{% endraw %}
