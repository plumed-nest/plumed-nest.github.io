**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s83 : argument O1O_lessthan was not set in pdb input
[runnervmmklqx:11723] *** Process received signal ***
[runnervmmklqx:11723] Signal: Aborted (6)
[runnervmmklqx:11723] Signal code:  (-6)
[runnervmmklqx:11723] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd84ec45330]
[runnervmmklqx:11723] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd84ec9eb2c]
[runnervmmklqx:11723] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd84ec4527e]
[runnervmmklqx:11723] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd84ec288ff]
[runnervmmklqx:11723] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd84f0a5ff5]
[runnervmmklqx:11723] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd84f0bb0da]
[runnervmmklqx:11723] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd84f0a5a55]
[runnervmmklqx:11723] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd84f0a5a6f]
[runnervmmklqx:11723] [ 8] plumed_master(+0x146dd)[0x5627344eb6dd]
[runnervmmklqx:11723] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd84ec2a1ca]
[runnervmmklqx:11723] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd84ec2a28b]
[runnervmmklqx:11723] [11] plumed_master(+0x15365)[0x5627344ec365]
[runnervmmklqx:11723] *** End of error message ***
</pre>
{% endraw %}
