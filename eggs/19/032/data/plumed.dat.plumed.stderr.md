**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[runnervm0kj6c:11339] *** Process received signal ***
[runnervm0kj6c:11339] Signal: Aborted (6)
[runnervm0kj6c:11339] Signal code:  (-6)
[runnervm0kj6c:11339] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f06f3245330]
[runnervm0kj6c:11339] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f06f329eb2c]
[runnervm0kj6c:11339] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f06f324527e]
[runnervm0kj6c:11339] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f06f32288ff]
[runnervm0kj6c:11339] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f06f36a5ff5]
[runnervm0kj6c:11339] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f06f36bb0da]
[runnervm0kj6c:11339] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f06f36a5a55]
[runnervm0kj6c:11339] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f06f36a5a6f]
[runnervm0kj6c:11339] [ 8] plumed(+0x146dd)[0x557e6c7eb6dd]
[runnervm0kj6c:11339] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f06f322a1ca]
[runnervm0kj6c:11339] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f06f322a28b]
[runnervm0kj6c:11339] [11] plumed(+0x15365)[0x557e6c7ec365]
[runnervm0kj6c:11339] *** End of error message ***
</pre>
{% endraw %}
