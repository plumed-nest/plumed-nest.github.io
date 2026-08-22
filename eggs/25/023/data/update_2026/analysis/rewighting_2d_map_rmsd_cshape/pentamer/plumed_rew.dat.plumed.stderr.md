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
[runnervm76f27:05121] *** Process received signal ***
[runnervm76f27:05121] Signal: Aborted (6)
[runnervm76f27:05121] Signal code:  (-6)
[runnervm76f27:05121] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2b83845330]
[runnervm76f27:05121] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2b8389ec0c]
[runnervm76f27:05121] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2b8384527e]
[runnervm76f27:05121] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2b838288ff]
[runnervm76f27:05121] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2b83ca5ff5]
[runnervm76f27:05121] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2b83cbb0da]
[runnervm76f27:05121] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2b83ca5a55]
[runnervm76f27:05121] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2b83ca5a6f]
[runnervm76f27:05121] [ 8] plumed(+0x146dd)[0x55b63b6336dd]
[runnervm76f27:05121] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2b8382a1ca]
[runnervm76f27:05121] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2b8382a28b]
[runnervm76f27:05121] [11] plumed(+0x15365)[0x55b63b634365]
[runnervm76f27:05121] *** End of error message ***
</pre>
{% endraw %}
