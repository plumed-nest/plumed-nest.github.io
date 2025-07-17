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
[pkrvmq0rgcvqdmg:13158] *** Process received signal ***
[pkrvmq0rgcvqdmg:13158] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:13158] Signal code:  (-6)
[pkrvmq0rgcvqdmg:13158] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f97cca45330]
[pkrvmq0rgcvqdmg:13158] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f97cca9eb2c]
[pkrvmq0rgcvqdmg:13158] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f97cca4527e]
[pkrvmq0rgcvqdmg:13158] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97cca288ff]
[pkrvmq0rgcvqdmg:13158] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f97ccea5ff5]
[pkrvmq0rgcvqdmg:13158] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f97ccebb0da]
[pkrvmq0rgcvqdmg:13158] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f97ccea5a55]
[pkrvmq0rgcvqdmg:13158] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f97ccea5a6f]
[pkrvmq0rgcvqdmg:13158] [ 8] plumed(+0x146dd)[0x55e4cb1c96dd]
[pkrvmq0rgcvqdmg:13158] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f97cca2a1ca]
[pkrvmq0rgcvqdmg:13158] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f97cca2a28b]
[pkrvmq0rgcvqdmg:13158] [11] plumed(+0x15365)[0x55e4cb1ca365]
[pkrvmq0rgcvqdmg:13158] *** End of error message ***
</pre>
{% endraw %}
