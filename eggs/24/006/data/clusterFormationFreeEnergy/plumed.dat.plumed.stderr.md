**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[runnervm0kj6c:04808] *** Process received signal ***
[runnervm0kj6c:04808] Signal: Aborted (6)
[runnervm0kj6c:04808] Signal code:  (-6)
[runnervm0kj6c:04808] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3082e45330]
[runnervm0kj6c:04808] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3082e9eb2c]
[runnervm0kj6c:04808] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3082e4527e]
[runnervm0kj6c:04808] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3082e288ff]
[runnervm0kj6c:04808] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f30832a5ff5]
[runnervm0kj6c:04808] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f30832bb0da]
[runnervm0kj6c:04808] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f30832a5a55]
[runnervm0kj6c:04808] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f30832a5a6f]
[runnervm0kj6c:04808] [ 8] plumed(+0x146dd)[0x55c223fe36dd]
[runnervm0kj6c:04808] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3082e2a1ca]
[runnervm0kj6c:04808] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3082e2a28b]
[runnervm0kj6c:04808] [11] plumed(+0x15365)[0x55c223fe4365]
[runnervm0kj6c:04808] *** End of error message ***
</pre>
{% endraw %}
