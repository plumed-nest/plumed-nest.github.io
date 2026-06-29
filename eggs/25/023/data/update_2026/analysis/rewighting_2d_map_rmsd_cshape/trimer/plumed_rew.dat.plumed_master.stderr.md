**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/trimer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s24 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:04689] *** Process received signal ***
[runnervmmklqx:04689] Signal: Aborted (6)
[runnervmmklqx:04689] Signal code:  (-6)
[runnervmmklqx:04689] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb803c45330]
[runnervmmklqx:04689] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb803c9eb2c]
[runnervmmklqx:04689] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb803c4527e]
[runnervmmklqx:04689] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb803c288ff]
[runnervmmklqx:04689] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8040a5ff5]
[runnervmmklqx:04689] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8040bb0da]
[runnervmmklqx:04689] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8040a5a55]
[runnervmmklqx:04689] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8040a5a6f]
[runnervmmklqx:04689] [ 8] plumed_master(+0x146dd)[0x56256effd6dd]
[runnervmmklqx:04689] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb803c2a1ca]
[runnervmmklqx:04689] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb803c2a28b]
[runnervmmklqx:04689] [11] plumed_master(+0x15365)[0x56256effe365]
[runnervmmklqx:04689] *** End of error message ***
</pre>
{% endraw %}
