**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[runnervm0kj6c:05251] *** Process received signal ***
[runnervm0kj6c:05251] Signal: Aborted (6)
[runnervm0kj6c:05251] Signal code:  (-6)
[runnervm0kj6c:05251] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f651ce45330]
[runnervm0kj6c:05251] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f651ce9eb2c]
[runnervm0kj6c:05251] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f651ce4527e]
[runnervm0kj6c:05251] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f651ce288ff]
[runnervm0kj6c:05251] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f651d2a5ff5]
[runnervm0kj6c:05251] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f651d2bb0da]
[runnervm0kj6c:05251] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f651d2a5a55]
[runnervm0kj6c:05251] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f651d2a5a6f]
[runnervm0kj6c:05251] [ 8] plumed_master(+0x146dd)[0x5633f36326dd]
[runnervm0kj6c:05251] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f651ce2a1ca]
[runnervm0kj6c:05251] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f651ce2a28b]
[runnervm0kj6c:05251] [11] plumed_master(+0x15365)[0x5633f3633365]
[runnervm0kj6c:05251] *** End of error message ***
</pre>
{% endraw %}
