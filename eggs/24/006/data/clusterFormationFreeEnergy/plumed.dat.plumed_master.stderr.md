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
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[fv-az1215-453:04009] *** Process received signal ***
[fv-az1215-453:04009] Signal: Aborted (6)
[fv-az1215-453:04009] Signal code:  (-6)
[fv-az1215-453:04009] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2f51842520]
[fv-az1215-453:04009] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f2f518969fc]
[fv-az1215-453:04009] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2f51842476]
[fv-az1215-453:04009] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f2f518287f3]
[fv-az1215-453:04009] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f2f51ca2b9e]
[fv-az1215-453:04009] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f2f51cae20c]
[fv-az1215-453:04009] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f2f51cae277]
[fv-az1215-453:04009] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f2f51cae52b]
[fv-az1215-453:04009] [ 8] plumed_master(+0x14274)[0x55acb5a68274]
[fv-az1215-453:04009] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2f51829d90]
[fv-az1215-453:04009] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2f51829e40]
[fv-az1215-453:04009] [11] plumed_master(+0x14ed5)[0x55acb5a68ed5]
[fv-az1215-453:04009] *** End of error message ***
</pre>
{% endraw %}
