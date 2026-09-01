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
[runnervmgx7h7:12237] *** Process received signal ***
[runnervmgx7h7:12237] Signal: Aborted (6)
[runnervmgx7h7:12237] Signal code:  (-6)
[runnervmgx7h7:12237] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa2ab045330]
[runnervmgx7h7:12237] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa2ab09ec0c]
[runnervmgx7h7:12237] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa2ab04527e]
[runnervmgx7h7:12237] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa2ab0288ff]
[runnervmgx7h7:12237] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa2ab4a5ff5]
[runnervmgx7h7:12237] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa2ab4bb0da]
[runnervmgx7h7:12237] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa2ab4a5a55]
[runnervmgx7h7:12237] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa2ab4a5a6f]
[runnervmgx7h7:12237] [ 8] plumed(+0x146dd)[0x5582513e86dd]
[runnervmgx7h7:12237] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa2ab02a1ca]
[runnervmgx7h7:12237] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa2ab02a28b]
[runnervmgx7h7:12237] [11] plumed(+0x15365)[0x5582513e9365]
[runnervmgx7h7:12237] *** End of error message ***
</pre>
{% endraw %}
