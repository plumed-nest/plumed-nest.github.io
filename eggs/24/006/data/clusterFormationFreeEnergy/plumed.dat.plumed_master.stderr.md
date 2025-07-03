**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:06197] *** Process received signal ***
[pkrvmbietmlfzoi:06197] Signal: Aborted (6)
[pkrvmbietmlfzoi:06197] Signal code:  (-6)
[pkrvmbietmlfzoi:06197] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f427f845330]
[pkrvmbietmlfzoi:06197] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f427f89eb2c]
[pkrvmbietmlfzoi:06197] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f427f84527e]
[pkrvmbietmlfzoi:06197] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f427f8288ff]
[pkrvmbietmlfzoi:06197] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f427fca5ff5]
[pkrvmbietmlfzoi:06197] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f427fcbb0da]
[pkrvmbietmlfzoi:06197] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f427fca5a55]
[pkrvmbietmlfzoi:06197] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f427fca5a6f]
[pkrvmbietmlfzoi:06197] [ 8] plumed_master(+0x146dd)[0x5601135286dd]
[pkrvmbietmlfzoi:06197] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f427f82a1ca]
[pkrvmbietmlfzoi:06197] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f427f82a28b]
[pkrvmbietmlfzoi:06197] [11] plumed_master(+0x15365)[0x560113529365]
[pkrvmbietmlfzoi:06197] *** End of error message ***
</pre>
{% endraw %}
