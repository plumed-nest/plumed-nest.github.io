**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:07850] *** Process received signal ***
[pkrvmpptgkbjq6m:07850] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07850] Signal code:  (-6)
[pkrvmpptgkbjq6m:07850] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fba74a45330]
[pkrvmpptgkbjq6m:07850] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fba74a9eb2c]
[pkrvmpptgkbjq6m:07850] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fba74a4527e]
[pkrvmpptgkbjq6m:07850] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fba74a288ff]
[pkrvmpptgkbjq6m:07850] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fba74ea5ff5]
[pkrvmpptgkbjq6m:07850] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fba74ebb0da]
[pkrvmpptgkbjq6m:07850] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fba74ea5a55]
[pkrvmpptgkbjq6m:07850] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fba74ea5a6f]
[pkrvmpptgkbjq6m:07850] [ 8] plumed(+0x146dd)[0x56403263b6dd]
[pkrvmpptgkbjq6m:07850] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fba74a2a1ca]
[pkrvmpptgkbjq6m:07850] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fba74a2a28b]
[pkrvmpptgkbjq6m:07850] [11] plumed(+0x15365)[0x56403263c365]
[pkrvmpptgkbjq6m:07850] *** End of error message ***
</pre>
{% endraw %}
