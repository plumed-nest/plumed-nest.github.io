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
[runnervmkj6or:12680] *** Process received signal ***
[runnervmkj6or:12680] Signal: Aborted (6)
[runnervmkj6or:12680] Signal code:  (-6)
[runnervmkj6or:12680] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbdf9c45330]
[runnervmkj6or:12680] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbdf9c9eb2c]
[runnervmkj6or:12680] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbdf9c4527e]
[runnervmkj6or:12680] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbdf9c288ff]
[runnervmkj6or:12680] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbdfa0a5ff5]
[runnervmkj6or:12680] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbdfa0bb0da]
[runnervmkj6or:12680] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbdfa0a5a55]
[runnervmkj6or:12680] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbdfa0a5a6f]
[runnervmkj6or:12680] [ 8] plumed_master(+0x146dd)[0x557518b4e6dd]
[runnervmkj6or:12680] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbdf9c2a1ca]
[runnervmkj6or:12680] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbdf9c2a28b]
[runnervmkj6or:12680] [11] plumed_master(+0x15365)[0x557518b4f365]
[runnervmkj6or:12680] *** End of error message ***
</pre>
{% endraw %}
