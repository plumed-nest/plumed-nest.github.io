**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/tetramer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @38 : keyword ARG is compulsory for this action
[runnervm0kj6c:04596] *** Process received signal ***
[runnervm0kj6c:04596] Signal: Aborted (6)
[runnervm0kj6c:04596] Signal code:  (-6)
[runnervm0kj6c:04596] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1cf3a45330]
[runnervm0kj6c:04596] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1cf3a9eb2c]
[runnervm0kj6c:04596] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1cf3a4527e]
[runnervm0kj6c:04596] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1cf3a288ff]
[runnervm0kj6c:04596] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1cf3ea5ff5]
[runnervm0kj6c:04596] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1cf3ebb0da]
[runnervm0kj6c:04596] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1cf3ea5a55]
[runnervm0kj6c:04596] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1cf3ea5a6f]
[runnervm0kj6c:04596] [ 8] plumed_master(+0x146dd)[0x5593a1b1c6dd]
[runnervm0kj6c:04596] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1cf3a2a1ca]
[runnervm0kj6c:04596] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1cf3a2a28b]
[runnervm0kj6c:04596] [11] plumed_master(+0x15365)[0x5593a1b1d365]
[runnervm0kj6c:04596] *** End of error message ***
</pre>
{% endraw %}
