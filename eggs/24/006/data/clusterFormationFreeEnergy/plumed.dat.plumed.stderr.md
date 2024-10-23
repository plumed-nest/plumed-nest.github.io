**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[fv-az975-395:04147] *** Process received signal ***
[fv-az975-395:04147] Signal: Aborted (6)
[fv-az975-395:04147] Signal code:  (-6)
[fv-az975-395:04147] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2a9ac42520]
[fv-az975-395:04147] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f2a9ac969fc]
[fv-az975-395:04147] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2a9ac42476]
[fv-az975-395:04147] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f2a9ac287f3]
[fv-az975-395:04147] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f2a9b0a2b9e]
[fv-az975-395:04147] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f2a9b0ae20c]
[fv-az975-395:04147] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f2a9b0ae277]
[fv-az975-395:04147] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f2a9b0ae52b]
[fv-az975-395:04147] [ 8] plumed(+0x14254)[0x55e99c210254]
[fv-az975-395:04147] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2a9ac29d90]
[fv-az975-395:04147] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2a9ac29e40]
[fv-az975-395:04147] [11] plumed(+0x14eb5)[0x55e99c210eb5]
[fv-az975-395:04147] *** End of error message ***
</pre>
{% endraw %}
