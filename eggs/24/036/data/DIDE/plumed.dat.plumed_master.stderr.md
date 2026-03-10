**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervm0kj6c:05957] *** Process received signal ***
[runnervm0kj6c:05957] Signal: Aborted (6)
[runnervm0kj6c:05957] Signal code:  (-6)
[runnervm0kj6c:05957] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0879a45330]
[runnervm0kj6c:05957] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0879a9eb2c]
[runnervm0kj6c:05957] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0879a4527e]
[runnervm0kj6c:05957] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0879a288ff]
[runnervm0kj6c:05957] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0879ea5ff5]
[runnervm0kj6c:05957] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0879ebb0da]
[runnervm0kj6c:05957] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0879ea5a55]
[runnervm0kj6c:05957] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0879ea5a6f]
[runnervm0kj6c:05957] [ 8] plumed_master(+0x146dd)[0x55e94e82c6dd]
[runnervm0kj6c:05957] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0879a2a1ca]
[runnervm0kj6c:05957] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0879a2a28b]
[runnervm0kj6c:05957] [11] plumed_master(+0x15365)[0x55e94e82d365]
[runnervm0kj6c:05957] *** End of error message ***
</pre>
{% endraw %}
