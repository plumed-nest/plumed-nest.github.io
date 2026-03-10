**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervm0kj6c:05387] *** Process received signal ***
[runnervm0kj6c:05387] Signal: Aborted (6)
[runnervm0kj6c:05387] Signal code:  (-6)
[runnervm0kj6c:05387] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7383e45330]
[runnervm0kj6c:05387] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7383e9eb2c]
[runnervm0kj6c:05387] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7383e4527e]
[runnervm0kj6c:05387] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7383e288ff]
[runnervm0kj6c:05387] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f73842a5ff5]
[runnervm0kj6c:05387] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f73842bb0da]
[runnervm0kj6c:05387] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f73842a5a55]
[runnervm0kj6c:05387] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f73842a5a6f]
[runnervm0kj6c:05387] [ 8] plumed(+0x146dd)[0x564b1c1d36dd]
[runnervm0kj6c:05387] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7383e2a1ca]
[runnervm0kj6c:05387] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7383e2a28b]
[runnervm0kj6c:05387] [11] plumed(+0x15365)[0x564b1c1d4365]
[runnervm0kj6c:05387] *** End of error message ***
</pre>
{% endraw %}
