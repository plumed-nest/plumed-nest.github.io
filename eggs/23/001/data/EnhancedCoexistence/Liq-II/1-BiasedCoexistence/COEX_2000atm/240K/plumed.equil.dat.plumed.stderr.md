**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.equil.dat   
Download: [zipped raw stdout](plumed.equil.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.equil.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmq0rgcvqdmg:08960] *** Process received signal ***
[pkrvmq0rgcvqdmg:08960] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08960] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08960] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff72ca45330]
[pkrvmq0rgcvqdmg:08960] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff72ca9eb2c]
[pkrvmq0rgcvqdmg:08960] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff72ca4527e]
[pkrvmq0rgcvqdmg:08960] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff72ca288ff]
[pkrvmq0rgcvqdmg:08960] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff72cea5ff5]
[pkrvmq0rgcvqdmg:08960] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff72cebb0da]
[pkrvmq0rgcvqdmg:08960] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff72cea5a55]
[pkrvmq0rgcvqdmg:08960] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff72cea5a6f]
[pkrvmq0rgcvqdmg:08960] [ 8] plumed(+0x146dd)[0x55f852d986dd]
[pkrvmq0rgcvqdmg:08960] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff72ca2a1ca]
[pkrvmq0rgcvqdmg:08960] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff72ca2a28b]
[pkrvmq0rgcvqdmg:08960] [11] plumed(+0x15365)[0x55f852d99365]
[pkrvmq0rgcvqdmg:08960] *** End of error message ***
</pre>
{% endraw %}
