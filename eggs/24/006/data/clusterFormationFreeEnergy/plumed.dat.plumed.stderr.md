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
[pkrvmxyh4eaekms:07905] *** Process received signal ***
[pkrvmxyh4eaekms:07905] Signal: Aborted (6)
[pkrvmxyh4eaekms:07905] Signal code:  (-6)
[pkrvmxyh4eaekms:07905] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcb84445330]
[pkrvmxyh4eaekms:07905] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcb8449eb2c]
[pkrvmxyh4eaekms:07905] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcb8444527e]
[pkrvmxyh4eaekms:07905] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcb844288ff]
[pkrvmxyh4eaekms:07905] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcb848a5ff5]
[pkrvmxyh4eaekms:07905] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcb848bb0da]
[pkrvmxyh4eaekms:07905] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcb848a5a55]
[pkrvmxyh4eaekms:07905] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcb848a5a6f]
[pkrvmxyh4eaekms:07905] [ 8] plumed(+0x146dd)[0x564f83e3e6dd]
[pkrvmxyh4eaekms:07905] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcb8442a1ca]
[pkrvmxyh4eaekms:07905] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcb8442a28b]
[pkrvmxyh4eaekms:07905] [11] plumed(+0x15365)[0x564f83e3f365]
[pkrvmxyh4eaekms:07905] *** End of error message ***
</pre>
{% endraw %}
