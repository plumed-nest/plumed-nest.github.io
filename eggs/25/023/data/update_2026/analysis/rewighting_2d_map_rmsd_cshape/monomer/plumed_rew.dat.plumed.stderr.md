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
[runnervm76f27:05065] *** Process received signal ***
[runnervm76f27:05065] Signal: Aborted (6)
[runnervm76f27:05065] Signal code:  (-6)
[runnervm76f27:05065] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc218e45330]
[runnervm76f27:05065] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc218e9ec0c]
[runnervm76f27:05065] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc218e4527e]
[runnervm76f27:05065] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc218e288ff]
[runnervm76f27:05065] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc2192a5ff5]
[runnervm76f27:05065] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc2192bb0da]
[runnervm76f27:05065] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc2192a5a55]
[runnervm76f27:05065] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc2192a5a6f]
[runnervm76f27:05065] [ 8] plumed(+0x146dd)[0x56350f7646dd]
[runnervm76f27:05065] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc218e2a1ca]
[runnervm76f27:05065] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc218e2a28b]
[runnervm76f27:05065] [11] plumed(+0x15365)[0x56350f765365]
[runnervm76f27:05065] *** End of error message ***
</pre>
{% endraw %}
