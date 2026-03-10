**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./amor/4-reweight_amor.dat   
Download: [zipped raw stdout](4-reweight_amor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](4-reweight_amor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[runnervm0kj6c:04251] *** Process received signal ***
[runnervm0kj6c:04251] Signal: Aborted (6)
[runnervm0kj6c:04251] Signal code:  (-6)
[runnervm0kj6c:04251] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2226a45330]
[runnervm0kj6c:04251] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2226a9eb2c]
[runnervm0kj6c:04251] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2226a4527e]
[runnervm0kj6c:04251] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2226a288ff]
[runnervm0kj6c:04251] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2226ea5ff5]
[runnervm0kj6c:04251] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2226ebb0da]
[runnervm0kj6c:04251] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2226ea5a55]
[runnervm0kj6c:04251] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2226ea5a6f]
[runnervm0kj6c:04251] [ 8] plumed_master(+0x146dd)[0x556f6aaa76dd]
[runnervm0kj6c:04251] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2226a2a1ca]
[runnervm0kj6c:04251] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2226a2a28b]
[runnervm0kj6c:04251] [11] plumed_master(+0x15365)[0x556f6aaa8365]
[runnervm0kj6c:04251] *** End of error message ***
</pre>
{% endraw %}
