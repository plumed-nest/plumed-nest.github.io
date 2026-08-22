**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/tetramer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s27 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:05204] *** Process received signal ***
[runnervm76f27:05204] Signal: Aborted (6)
[runnervm76f27:05204] Signal code:  (-6)
[runnervm76f27:05204] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0368645330]
[runnervm76f27:05204] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f036869ec0c]
[runnervm76f27:05204] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f036864527e]
[runnervm76f27:05204] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03686288ff]
[runnervm76f27:05204] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0368aa5ff5]
[runnervm76f27:05204] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0368abb0da]
[runnervm76f27:05204] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0368aa5a55]
[runnervm76f27:05204] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0368aa5a6f]
[runnervm76f27:05204] [ 8] plumed_master(+0x146dd)[0x5647af3536dd]
[runnervm76f27:05204] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f036862a1ca]
[runnervm76f27:05204] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f036862a28b]
[runnervm76f27:05204] [11] plumed_master(+0x15365)[0x5647af354365]
[runnervm76f27:05204] *** End of error message ***
</pre>
{% endraw %}
