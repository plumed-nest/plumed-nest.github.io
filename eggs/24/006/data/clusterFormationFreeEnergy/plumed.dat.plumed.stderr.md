**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[fv-az1937-158:61482] *** Process received signal ***
[fv-az1937-158:61482] Signal: Aborted (6)
[fv-az1937-158:61482] Signal code:  (-6)
[fv-az1937-158:61482] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcb58045330]
[fv-az1937-158:61482] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcb5809eb2c]
[fv-az1937-158:61482] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcb5804527e]
[fv-az1937-158:61482] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcb580288ff]
[fv-az1937-158:61482] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcb584a5ff5]
[fv-az1937-158:61482] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcb584bb0da]
[fv-az1937-158:61482] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcb584a5a55]
[fv-az1937-158:61482] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcb584a5a6f]
[fv-az1937-158:61482] [ 8] plumed(+0x146dd)[0x55904d5466dd]
[fv-az1937-158:61482] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcb5802a1ca]
[fv-az1937-158:61482] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcb5802a28b]
[fv-az1937-158:61482] [11] plumed(+0x15365)[0x55904d547365]
[fv-az1937-158:61482] *** End of error message ***
</pre>
{% endraw %}
