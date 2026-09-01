**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @150 : keyword ARG is compulsory for this action
[runnervmgx7h7:07008] *** Process received signal ***
[runnervmgx7h7:07008] Signal: Aborted (6)
[runnervmgx7h7:07008] Signal code:  (-6)
[runnervmgx7h7:07008] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d02645330]
[runnervmgx7h7:07008] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d0269ec0c]
[runnervmgx7h7:07008] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d0264527e]
[runnervmgx7h7:07008] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d026288ff]
[runnervmgx7h7:07008] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d02aa5ff5]
[runnervmgx7h7:07008] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d02abb0da]
[runnervmgx7h7:07008] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d02aa5a55]
[runnervmgx7h7:07008] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d02aa5a6f]
[runnervmgx7h7:07008] [ 8] plumed_master(+0x146dd)[0x55c6647cf6dd]
[runnervmgx7h7:07008] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d0262a1ca]
[runnervmgx7h7:07008] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d0262a28b]
[runnervmgx7h7:07008] [11] plumed_master(+0x15365)[0x55c6647d0365]
[runnervmgx7h7:07008] *** End of error message ***
</pre>
{% endraw %}
