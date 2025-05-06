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
[fv-az1696-883:63426] *** Process received signal ***
[fv-az1696-883:63426] Signal: Aborted (6)
[fv-az1696-883:63426] Signal code:  (-6)
[fv-az1696-883:63426] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f03dfc45330]
[fv-az1696-883:63426] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f03dfc9eb2c]
[fv-az1696-883:63426] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f03dfc4527e]
[fv-az1696-883:63426] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03dfc288ff]
[fv-az1696-883:63426] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f03e00a5ff5]
[fv-az1696-883:63426] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f03e00bb0da]
[fv-az1696-883:63426] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f03e00a5a55]
[fv-az1696-883:63426] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f03e00a5a6f]
[fv-az1696-883:63426] [ 8] plumed(+0x146dd)[0x55844a1886dd]
[fv-az1696-883:63426] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f03dfc2a1ca]
[fv-az1696-883:63426] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f03dfc2a28b]
[fv-az1696-883:63426] [11] plumed(+0x15365)[0x55844a189365]
[fv-az1696-883:63426] *** End of error message ***
</pre>
{% endraw %}
