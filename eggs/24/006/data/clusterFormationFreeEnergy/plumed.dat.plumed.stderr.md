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
[pkrvmbietmlfzoi:63742] *** Process received signal ***
[pkrvmbietmlfzoi:63742] Signal: Aborted (6)
[pkrvmbietmlfzoi:63742] Signal code:  (-6)
[pkrvmbietmlfzoi:63742] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8ef2045330]
[pkrvmbietmlfzoi:63742] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8ef209eb2c]
[pkrvmbietmlfzoi:63742] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8ef204527e]
[pkrvmbietmlfzoi:63742] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8ef20288ff]
[pkrvmbietmlfzoi:63742] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8ef24a5ff5]
[pkrvmbietmlfzoi:63742] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8ef24bb0da]
[pkrvmbietmlfzoi:63742] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8ef24a5a55]
[pkrvmbietmlfzoi:63742] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8ef24a5a6f]
[pkrvmbietmlfzoi:63742] [ 8] plumed(+0x146dd)[0x560f2d8f46dd]
[pkrvmbietmlfzoi:63742] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8ef202a1ca]
[pkrvmbietmlfzoi:63742] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8ef202a28b]
[pkrvmbietmlfzoi:63742] [11] plumed(+0x15365)[0x560f2d8f5365]
[pkrvmbietmlfzoi:63742] *** End of error message ***
</pre>
{% endraw %}
