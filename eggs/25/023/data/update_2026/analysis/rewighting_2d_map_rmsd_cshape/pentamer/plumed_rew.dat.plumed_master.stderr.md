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
[runnervmvrwv9:04773] *** Process received signal ***
[runnervmvrwv9:04773] Signal: Aborted (6)
[runnervmvrwv9:04773] Signal code:  (-6)
[runnervmvrwv9:04773] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2cf3645330]
[runnervmvrwv9:04773] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2cf369eb2c]
[runnervmvrwv9:04773] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2cf364527e]
[runnervmvrwv9:04773] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2cf36288ff]
[runnervmvrwv9:04773] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2cf3aa5ff5]
[runnervmvrwv9:04773] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2cf3abb0da]
[runnervmvrwv9:04773] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2cf3aa5a55]
[runnervmvrwv9:04773] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2cf3aa5a6f]
[runnervmvrwv9:04773] [ 8] plumed_master(+0x146dd)[0x56409e4c36dd]
[runnervmvrwv9:04773] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2cf362a1ca]
[runnervmvrwv9:04773] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2cf362a28b]
[runnervmvrwv9:04773] [11] plumed_master(+0x15365)[0x56409e4c4365]
[runnervmvrwv9:04773] *** End of error message ***
</pre>
{% endraw %}
