**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervm0kj6c:07397] *** Process received signal ***
[runnervm0kj6c:07397] Signal: Aborted (6)
[runnervm0kj6c:07397] Signal code:  (-6)
[runnervm0kj6c:07397] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2dd3e45330]
[runnervm0kj6c:07397] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2dd3e9eb2c]
[runnervm0kj6c:07397] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2dd3e4527e]
[runnervm0kj6c:07397] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2dd3e288ff]
[runnervm0kj6c:07397] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2dd42a5ff5]
[runnervm0kj6c:07397] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2dd42bb0da]
[runnervm0kj6c:07397] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2dd42a5a55]
[runnervm0kj6c:07397] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2dd42a5a6f]
[runnervm0kj6c:07397] [ 8] plumed_master(+0x146dd)[0x55cc1e8606dd]
[runnervm0kj6c:07397] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2dd3e2a1ca]
[runnervm0kj6c:07397] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2dd3e2a28b]
[runnervm0kj6c:07397] [11] plumed_master(+0x15365)[0x55cc1e861365]
[runnervm0kj6c:07397] *** End of error message ***
</pre>
{% endraw %}
