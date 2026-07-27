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
[runnervmvrwv9:04860] *** Process received signal ***
[runnervmvrwv9:04860] Signal: Aborted (6)
[runnervmvrwv9:04860] Signal code:  (-6)
[runnervmvrwv9:04860] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f99abc45330]
[runnervmvrwv9:04860] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f99abc9eb2c]
[runnervmvrwv9:04860] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f99abc4527e]
[runnervmvrwv9:04860] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f99abc288ff]
[runnervmvrwv9:04860] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f99ac0a5ff5]
[runnervmvrwv9:04860] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f99ac0bb0da]
[runnervmvrwv9:04860] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f99ac0a5a55]
[runnervmvrwv9:04860] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f99ac0a5a6f]
[runnervmvrwv9:04860] [ 8] plumed(+0x146dd)[0x55a7947a46dd]
[runnervmvrwv9:04860] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f99abc2a1ca]
[runnervmvrwv9:04860] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f99abc2a28b]
[runnervmvrwv9:04860] [11] plumed(+0x15365)[0x55a7947a5365]
[runnervmvrwv9:04860] *** End of error message ***
</pre>
{% endraw %}
