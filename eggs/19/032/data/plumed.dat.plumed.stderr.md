**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[runnervmmklqx:11707] *** Process received signal ***
[runnervmmklqx:11707] Signal: Aborted (6)
[runnervmmklqx:11707] Signal code:  (-6)
[runnervmmklqx:11707] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff64d445330]
[runnervmmklqx:11707] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff64d49eb2c]
[runnervmmklqx:11707] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff64d44527e]
[runnervmmklqx:11707] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff64d4288ff]
[runnervmmklqx:11707] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff64d8a5ff5]
[runnervmmklqx:11707] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff64d8bb0da]
[runnervmmklqx:11707] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff64d8a5a55]
[runnervmmklqx:11707] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff64d8a5a6f]
[runnervmmklqx:11707] [ 8] plumed(+0x146dd)[0x55f4dbac76dd]
[runnervmmklqx:11707] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff64d42a1ca]
[runnervmmklqx:11707] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff64d42a28b]
[runnervmmklqx:11707] [11] plumed(+0x15365)[0x55f4dbac8365]
[runnervmmklqx:11707] *** End of error message ***
</pre>
{% endraw %}
