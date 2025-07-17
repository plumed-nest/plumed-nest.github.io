**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[pkrvmq0rgcvqdmg:08908] *** Process received signal ***
[pkrvmq0rgcvqdmg:08908] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08908] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08908] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7da9045330]
[pkrvmq0rgcvqdmg:08908] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7da909eb2c]
[pkrvmq0rgcvqdmg:08908] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7da904527e]
[pkrvmq0rgcvqdmg:08908] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7da90288ff]
[pkrvmq0rgcvqdmg:08908] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7da94a5ff5]
[pkrvmq0rgcvqdmg:08908] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7da94bb0da]
[pkrvmq0rgcvqdmg:08908] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7da94a5a55]
[pkrvmq0rgcvqdmg:08908] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7da94a5a6f]
[pkrvmq0rgcvqdmg:08908] [ 8] plumed(+0x146dd)[0x55cd648c16dd]
[pkrvmq0rgcvqdmg:08908] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7da902a1ca]
[pkrvmq0rgcvqdmg:08908] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7da902a28b]
[pkrvmq0rgcvqdmg:08908] [11] plumed(+0x15365)[0x55cd648c2365]
[pkrvmq0rgcvqdmg:08908] *** End of error message ***
</pre>
{% endraw %}
