**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s29 : cannot understand the following words from the input line : LOWMEM
[runnervm0kj6c:08762] *** Process received signal ***
[runnervm0kj6c:08762] Signal: Aborted (6)
[runnervm0kj6c:08762] Signal code:  (-6)
[runnervm0kj6c:08762] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4321645330]
[runnervm0kj6c:08762] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f432169eb2c]
[runnervm0kj6c:08762] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f432164527e]
[runnervm0kj6c:08762] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f43216288ff]
[runnervm0kj6c:08762] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4321aa5ff5]
[runnervm0kj6c:08762] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4321abb0da]
[runnervm0kj6c:08762] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4321aa5a55]
[runnervm0kj6c:08762] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4321aa5a6f]
[runnervm0kj6c:08762] [ 8] plumed_master(+0x146dd)[0x564a8920a6dd]
[runnervm0kj6c:08762] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f432162a1ca]
[runnervm0kj6c:08762] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f432162a28b]
[runnervm0kj6c:08762] [11] plumed_master(+0x15365)[0x564a8920b365]
[runnervm0kj6c:08762] *** End of error message ***
</pre>
{% endraw %}
