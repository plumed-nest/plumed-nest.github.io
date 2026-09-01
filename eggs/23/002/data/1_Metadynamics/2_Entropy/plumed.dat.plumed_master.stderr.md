**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[runnervmgx7h7:05668] *** Process received signal ***
[runnervmgx7h7:05668] Signal: Aborted (6)
[runnervmgx7h7:05668] Signal code:  (-6)
[runnervmgx7h7:05668] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0b41245330]
[runnervmgx7h7:05668] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0b4129ec0c]
[runnervmgx7h7:05668] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0b4124527e]
[runnervmgx7h7:05668] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0b412288ff]
[runnervmgx7h7:05668] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0b416a5ff5]
[runnervmgx7h7:05668] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0b416bb0da]
[runnervmgx7h7:05668] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0b416a5a55]
[runnervmgx7h7:05668] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0b416a5a6f]
[runnervmgx7h7:05668] [ 8] plumed_master(+0x146dd)[0x564cad98c6dd]
[runnervmgx7h7:05668] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0b4122a1ca]
[runnervmgx7h7:05668] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0b4122a28b]
[runnervmgx7h7:05668] [11] plumed_master(+0x15365)[0x564cad98d365]
[runnervmgx7h7:05668] *** End of error message ***
</pre>
{% endraw %}
