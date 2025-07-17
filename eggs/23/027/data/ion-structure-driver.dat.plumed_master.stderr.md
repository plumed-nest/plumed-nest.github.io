**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[pkrvmq0rgcvqdmg:08224] *** Process received signal ***
[pkrvmq0rgcvqdmg:08224] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:08224] Signal code:  (-6)
[pkrvmq0rgcvqdmg:08224] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3fce645330]
[pkrvmq0rgcvqdmg:08224] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3fce69eb2c]
[pkrvmq0rgcvqdmg:08224] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3fce64527e]
[pkrvmq0rgcvqdmg:08224] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3fce6288ff]
[pkrvmq0rgcvqdmg:08224] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3fceaa5ff5]
[pkrvmq0rgcvqdmg:08224] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3fceabb0da]
[pkrvmq0rgcvqdmg:08224] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3fceaa5a55]
[pkrvmq0rgcvqdmg:08224] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3fceaa5a6f]
[pkrvmq0rgcvqdmg:08224] [ 8] plumed_master(+0x146dd)[0x55ab3081d6dd]
[pkrvmq0rgcvqdmg:08224] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3fce62a1ca]
[pkrvmq0rgcvqdmg:08224] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3fce62a28b]
[pkrvmq0rgcvqdmg:08224] [11] plumed_master(+0x15365)[0x55ab3081e365]
[pkrvmq0rgcvqdmg:08224] *** End of error message ***
</pre>
{% endraw %}
