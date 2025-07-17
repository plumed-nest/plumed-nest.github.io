**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[pkrvmq0rgcvqdmg:06124] *** Process received signal ***
[pkrvmq0rgcvqdmg:06124] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06124] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06124] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0106645330]
[pkrvmq0rgcvqdmg:06124] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f010669eb2c]
[pkrvmq0rgcvqdmg:06124] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f010664527e]
[pkrvmq0rgcvqdmg:06124] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f01066288ff]
[pkrvmq0rgcvqdmg:06124] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0106aa5ff5]
[pkrvmq0rgcvqdmg:06124] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0106abb0da]
[pkrvmq0rgcvqdmg:06124] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0106aa5a55]
[pkrvmq0rgcvqdmg:06124] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0106aa5a6f]
[pkrvmq0rgcvqdmg:06124] [ 8] plumed_master(+0x146dd)[0x55570e2f46dd]
[pkrvmq0rgcvqdmg:06124] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f010662a1ca]
[pkrvmq0rgcvqdmg:06124] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f010662a28b]
[pkrvmq0rgcvqdmg:06124] [11] plumed_master(+0x15365)[0x55570e2f5365]
[pkrvmq0rgcvqdmg:06124] *** End of error message ***
</pre>
{% endraw %}
