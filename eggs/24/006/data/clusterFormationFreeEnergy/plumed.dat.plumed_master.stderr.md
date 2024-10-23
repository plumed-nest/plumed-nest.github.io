**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[fv-az975-395:04155] *** Process received signal ***
[fv-az975-395:04155] Signal: Aborted (6)
[fv-az975-395:04155] Signal code:  (-6)
[fv-az975-395:04155] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7a7a842520]
[fv-az975-395:04155] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7a7a8969fc]
[fv-az975-395:04155] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7a7a842476]
[fv-az975-395:04155] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7a7a8287f3]
[fv-az975-395:04155] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7a7aca2b9e]
[fv-az975-395:04155] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7a7acae20c]
[fv-az975-395:04155] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7a7acae277]
[fv-az975-395:04155] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7a7acae52b]
[fv-az975-395:04155] [ 8] plumed_master(+0x14254)[0x55f41514d254]
[fv-az975-395:04155] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7a7a829d90]
[fv-az975-395:04155] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7a7a829e40]
[fv-az975-395:04155] [11] plumed_master(+0x14eb5)[0x55f41514deb5]
[fv-az975-395:04155] *** End of error message ***
</pre>
{% endraw %}
