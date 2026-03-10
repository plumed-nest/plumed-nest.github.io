**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[runnervm0kj6c:05925] *** Process received signal ***
[runnervm0kj6c:05925] Signal: Aborted (6)
[runnervm0kj6c:05925] Signal code:  (-6)
[runnervm0kj6c:05925] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0e76045330]
[runnervm0kj6c:05925] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0e7609eb2c]
[runnervm0kj6c:05925] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0e7604527e]
[runnervm0kj6c:05925] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0e760288ff]
[runnervm0kj6c:05925] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0e764a5ff5]
[runnervm0kj6c:05925] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0e764bb0da]
[runnervm0kj6c:05925] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0e764a5a55]
[runnervm0kj6c:05925] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0e764a5a6f]
[runnervm0kj6c:05925] [ 8] plumed_master(+0x146dd)[0x5597fe67c6dd]
[runnervm0kj6c:05925] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0e7602a1ca]
[runnervm0kj6c:05925] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0e7602a28b]
[runnervm0kj6c:05925] [11] plumed_master(+0x15365)[0x5597fe67d365]
[runnervm0kj6c:05925] *** End of error message ***
</pre>
{% endraw %}
