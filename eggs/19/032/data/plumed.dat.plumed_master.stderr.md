**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s83 : argument O1O_lessthan was not set in pdb input
[runnervm0kj6c:11355] *** Process received signal ***
[runnervm0kj6c:11355] Signal: Aborted (6)
[runnervm0kj6c:11355] Signal code:  (-6)
[runnervm0kj6c:11355] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f683fc45330]
[runnervm0kj6c:11355] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f683fc9eb2c]
[runnervm0kj6c:11355] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f683fc4527e]
[runnervm0kj6c:11355] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f683fc288ff]
[runnervm0kj6c:11355] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68400a5ff5]
[runnervm0kj6c:11355] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68400bb0da]
[runnervm0kj6c:11355] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68400a5a55]
[runnervm0kj6c:11355] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68400a5a6f]
[runnervm0kj6c:11355] [ 8] plumed_master(+0x146dd)[0x55e8c742c6dd]
[runnervm0kj6c:11355] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f683fc2a1ca]
[runnervm0kj6c:11355] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f683fc2a28b]
[runnervm0kj6c:11355] [11] plumed_master(+0x15365)[0x55e8c742d365]
[runnervm0kj6c:11355] *** End of error message ***
</pre>
{% endraw %}
