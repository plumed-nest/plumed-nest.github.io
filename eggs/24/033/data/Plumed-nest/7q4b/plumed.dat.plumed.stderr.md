**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervm0kj6c:05235] *** Process received signal ***
[runnervm0kj6c:05235] Signal: Aborted (6)
[runnervm0kj6c:05235] Signal code:  (-6)
[runnervm0kj6c:05235] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d39e45330]
[runnervm0kj6c:05235] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d39e9eb2c]
[runnervm0kj6c:05235] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d39e4527e]
[runnervm0kj6c:05235] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d39e288ff]
[runnervm0kj6c:05235] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d3a2a5ff5]
[runnervm0kj6c:05235] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d3a2bb0da]
[runnervm0kj6c:05235] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d3a2a5a55]
[runnervm0kj6c:05235] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d3a2a5a6f]
[runnervm0kj6c:05235] [ 8] plumed(+0x146dd)[0x560631eac6dd]
[runnervm0kj6c:05235] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d39e2a1ca]
[runnervm0kj6c:05235] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d39e2a28b]
[runnervm0kj6c:05235] [11] plumed(+0x15365)[0x560631ead365]
[runnervm0kj6c:05235] *** End of error message ***
</pre>
{% endraw %}
