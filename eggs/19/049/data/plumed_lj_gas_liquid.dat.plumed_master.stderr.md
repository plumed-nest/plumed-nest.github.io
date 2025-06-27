**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:69139] *** Process received signal ***
[pkrvmbietmlfzoi:69139] Signal: Aborted (6)
[pkrvmbietmlfzoi:69139] Signal code:  (-6)
[pkrvmbietmlfzoi:69139] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe627c45330]
[pkrvmbietmlfzoi:69139] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe627c9eb2c]
[pkrvmbietmlfzoi:69139] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe627c4527e]
[pkrvmbietmlfzoi:69139] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe627c288ff]
[pkrvmbietmlfzoi:69139] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe6280a5ff5]
[pkrvmbietmlfzoi:69139] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe6280bb0da]
[pkrvmbietmlfzoi:69139] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe6280a5a55]
[pkrvmbietmlfzoi:69139] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe6280a5a6f]
[pkrvmbietmlfzoi:69139] [ 8] plumed_master(+0x146dd)[0x55cfd6dcc6dd]
[pkrvmbietmlfzoi:69139] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe627c2a1ca]
[pkrvmbietmlfzoi:69139] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe627c2a28b]
[pkrvmbietmlfzoi:69139] [11] plumed_master(+0x15365)[0x55cfd6dcd365]
[pkrvmbietmlfzoi:69139] *** End of error message ***
</pre>
{% endraw %}
