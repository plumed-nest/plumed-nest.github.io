**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/monomer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s16 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:04706] *** Process received signal ***
[runnervmvrwv9:04706] Signal: Aborted (6)
[runnervmvrwv9:04706] Signal code:  (-6)
[runnervmvrwv9:04706] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd20cc45330]
[runnervmvrwv9:04706] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd20cc9eb2c]
[runnervmvrwv9:04706] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd20cc4527e]
[runnervmvrwv9:04706] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd20cc288ff]
[runnervmvrwv9:04706] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd20d0a5ff5]
[runnervmvrwv9:04706] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd20d0bb0da]
[runnervmvrwv9:04706] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd20d0a5a55]
[runnervmvrwv9:04706] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd20d0a5a6f]
[runnervmvrwv9:04706] [ 8] plumed(+0x146dd)[0x559d5fa0a6dd]
[runnervmvrwv9:04706] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd20cc2a1ca]
[runnervmvrwv9:04706] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd20cc2a28b]
[runnervmvrwv9:04706] [11] plumed(+0x15365)[0x559d5fa0b365]
[runnervmvrwv9:04706] *** End of error message ***
</pre>
{% endraw %}
