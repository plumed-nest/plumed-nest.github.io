**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/monomer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @27 : keyword ARG is compulsory for this action
[runnervm0kj6c:04516] *** Process received signal ***
[runnervm0kj6c:04516] Signal: Aborted (6)
[runnervm0kj6c:04516] Signal code:  (-6)
[runnervm0kj6c:04516] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6e50245330]
[runnervm0kj6c:04516] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6e5029eb2c]
[runnervm0kj6c:04516] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6e5024527e]
[runnervm0kj6c:04516] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6e502288ff]
[runnervm0kj6c:04516] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6e506a5ff5]
[runnervm0kj6c:04516] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6e506bb0da]
[runnervm0kj6c:04516] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6e506a5a55]
[runnervm0kj6c:04516] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6e506a5a6f]
[runnervm0kj6c:04516] [ 8] plumed_master(+0x146dd)[0x562a02c556dd]
[runnervm0kj6c:04516] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6e5022a1ca]
[runnervm0kj6c:04516] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6e5022a28b]
[runnervm0kj6c:04516] [11] plumed_master(+0x15365)[0x562a02c56365]
[runnervm0kj6c:04516] *** End of error message ***
</pre>
{% endraw %}
