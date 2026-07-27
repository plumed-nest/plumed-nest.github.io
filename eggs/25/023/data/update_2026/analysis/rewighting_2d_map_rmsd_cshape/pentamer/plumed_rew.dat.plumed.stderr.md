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
[runnervmvrwv9:04757] *** Process received signal ***
[runnervmvrwv9:04757] Signal: Aborted (6)
[runnervmvrwv9:04757] Signal code:  (-6)
[runnervmvrwv9:04757] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9d7da45330]
[runnervmvrwv9:04757] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9d7da9eb2c]
[runnervmvrwv9:04757] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9d7da4527e]
[runnervmvrwv9:04757] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9d7da288ff]
[runnervmvrwv9:04757] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9d7dea5ff5]
[runnervmvrwv9:04757] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9d7debb0da]
[runnervmvrwv9:04757] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9d7dea5a55]
[runnervmvrwv9:04757] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9d7dea5a6f]
[runnervmvrwv9:04757] [ 8] plumed(+0x146dd)[0x55a9601a76dd]
[runnervmvrwv9:04757] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9d7da2a1ca]
[runnervmvrwv9:04757] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9d7da2a28b]
[runnervmvrwv9:04757] [11] plumed(+0x15365)[0x55a9601a8365]
[runnervmvrwv9:04757] *** End of error message ***
</pre>
{% endraw %}
