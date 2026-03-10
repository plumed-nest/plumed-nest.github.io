**Project ID:** [plumID:25.023]({{ '/' | absolute_url }}eggs/25/023/)  
Stderr for source:  update_2026/analysis/rewighting_2d_map_rmsd_cshape/pentamer/plumed_rew.dat   
Download: [zipped raw stdout](plumed_rew.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_rew.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @41 : keyword ARG is compulsory for this action
[runnervm0kj6c:04554] *** Process received signal ***
[runnervm0kj6c:04554] Signal: Aborted (6)
[runnervm0kj6c:04554] Signal code:  (-6)
[runnervm0kj6c:04554] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd6a6a45330]
[runnervm0kj6c:04554] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd6a6a9eb2c]
[runnervm0kj6c:04554] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd6a6a4527e]
[runnervm0kj6c:04554] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6a6a288ff]
[runnervm0kj6c:04554] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6a6ea5ff5]
[runnervm0kj6c:04554] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6a6ebb0da]
[runnervm0kj6c:04554] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6a6ea5a55]
[runnervm0kj6c:04554] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6a6ea5a6f]
[runnervm0kj6c:04554] [ 8] plumed_master(+0x146dd)[0x555ca0f2c6dd]
[runnervm0kj6c:04554] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd6a6a2a1ca]
[runnervm0kj6c:04554] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd6a6a2a28b]
[runnervm0kj6c:04554] [11] plumed_master(+0x15365)[0x555ca0f2d365]
[runnervm0kj6c:04554] *** End of error message ***
</pre>
{% endraw %}
