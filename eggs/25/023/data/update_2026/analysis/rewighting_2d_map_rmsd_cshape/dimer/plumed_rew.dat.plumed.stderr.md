**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/dimer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s21 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervm76f27:05013] *** Process received signal ***
[runnervm76f27:05013] Signal: Aborted (6)
[runnervm76f27:05013] Signal code:  (-6)
[runnervm76f27:05013] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23ce445330]
[runnervm76f27:05013] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23ce49ec0c]
[runnervm76f27:05013] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23ce44527e]
[runnervm76f27:05013] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23ce4288ff]
[runnervm76f27:05013] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23ce8a5ff5]
[runnervm76f27:05013] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23ce8bb0da]
[runnervm76f27:05013] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23ce8a5a55]
[runnervm76f27:05013] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23ce8a5a6f]
[runnervm76f27:05013] [ 8] plumed(+0x146dd)[0x564e017756dd]
[runnervm76f27:05013] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23ce42a1ca]
[runnervm76f27:05013] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23ce42a28b]
[runnervm76f27:05013] [11] plumed(+0x15365)[0x564e01776365]
[runnervm76f27:05013] *** End of error message ***
</pre>
{% endraw %}
