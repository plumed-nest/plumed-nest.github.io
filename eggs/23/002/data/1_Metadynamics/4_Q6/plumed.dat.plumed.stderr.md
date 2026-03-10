**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[runnervm0kj6c:08746] *** Process received signal ***
[runnervm0kj6c:08746] Signal: Aborted (6)
[runnervm0kj6c:08746] Signal code:  (-6)
[runnervm0kj6c:08746] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8382845330]
[runnervm0kj6c:08746] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f838289eb2c]
[runnervm0kj6c:08746] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f838284527e]
[runnervm0kj6c:08746] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83828288ff]
[runnervm0kj6c:08746] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8382ca5ff5]
[runnervm0kj6c:08746] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8382cbb0da]
[runnervm0kj6c:08746] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8382ca5a55]
[runnervm0kj6c:08746] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8382ca5a6f]
[runnervm0kj6c:08746] [ 8] plumed(+0x146dd)[0x55f4fab006dd]
[runnervm0kj6c:08746] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f838282a1ca]
[runnervm0kj6c:08746] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f838282a28b]
[runnervm0kj6c:08746] [11] plumed(+0x15365)[0x55f4fab01365]
[runnervm0kj6c:08746] *** End of error message ***
</pre>
{% endraw %}
