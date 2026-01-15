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
[runnervmmtnos:37786] *** Process received signal ***
[runnervmmtnos:37786] Signal: Aborted (6)
[runnervmmtnos:37786] Signal code:  (-6)
[runnervmmtnos:37786] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f904fa45330]
[runnervmmtnos:37786] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f904fa9eb2c]
[runnervmmtnos:37786] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f904fa4527e]
[runnervmmtnos:37786] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f904fa288ff]
[runnervmmtnos:37786] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f904fea5ff5]
[runnervmmtnos:37786] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f904febb0da]
[runnervmmtnos:37786] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f904fea5a55]
[runnervmmtnos:37786] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f904fea5a6f]
[runnervmmtnos:37786] [ 8] plumed(+0x146dd)[0x563037c536dd]
[runnervmmtnos:37786] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f904fa2a1ca]
[runnervmmtnos:37786] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f904fa2a28b]
[runnervmmtnos:37786] [11] plumed(+0x15365)[0x563037c54365]
[runnervmmtnos:37786] *** End of error message ***
</pre>
{% endraw %}
