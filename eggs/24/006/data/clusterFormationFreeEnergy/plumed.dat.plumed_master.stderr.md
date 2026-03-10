**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[runnervm0kj6c:04823] *** Process received signal ***
[runnervm0kj6c:04823] Signal: Aborted (6)
[runnervm0kj6c:04823] Signal code:  (-6)
[runnervm0kj6c:04823] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d08e45330]
[runnervm0kj6c:04823] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d08e9eb2c]
[runnervm0kj6c:04823] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d08e4527e]
[runnervm0kj6c:04823] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d08e288ff]
[runnervm0kj6c:04823] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d092a5ff5]
[runnervm0kj6c:04823] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d092bb0da]
[runnervm0kj6c:04823] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d092a5a55]
[runnervm0kj6c:04823] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d092a5a6f]
[runnervm0kj6c:04823] [ 8] plumed_master(+0x146dd)[0x55d71b9f06dd]
[runnervm0kj6c:04823] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d08e2a1ca]
[runnervm0kj6c:04823] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d08e2a28b]
[runnervm0kj6c:04823] [11] plumed_master(+0x15365)[0x55d71b9f1365]
[runnervm0kj6c:04823] *** End of error message ***
</pre>
{% endraw %}
