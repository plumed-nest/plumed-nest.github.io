**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[runnervmvrwv9:06024] *** Process received signal ***
[runnervmvrwv9:06024] Signal: Aborted (6)
[runnervmvrwv9:06024] Signal code:  (-6)
[runnervmvrwv9:06024] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5992045330]
[runnervmvrwv9:06024] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f599209eb2c]
[runnervmvrwv9:06024] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f599204527e]
[runnervmvrwv9:06024] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f59920288ff]
[runnervmvrwv9:06024] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f59924a5ff5]
[runnervmvrwv9:06024] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f59924bb0da]
[runnervmvrwv9:06024] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f59924a5a55]
[runnervmvrwv9:06024] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f59924a5a6f]
[runnervmvrwv9:06024] [ 8] plumed(+0x146dd)[0x55c1facb66dd]
[runnervmvrwv9:06024] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f599202a1ca]
[runnervmvrwv9:06024] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f599202a28b]
[runnervmvrwv9:06024] [11] plumed(+0x15365)[0x55c1facb7365]
[runnervmvrwv9:06024] *** End of error message ***
</pre>
{% endraw %}
