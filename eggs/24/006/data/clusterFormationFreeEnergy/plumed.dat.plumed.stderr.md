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
[runnervmmtnos:32218] *** Process received signal ***
[runnervmmtnos:32218] Signal: Aborted (6)
[runnervmmtnos:32218] Signal code:  (-6)
[runnervmmtnos:32218] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c9ec45330]
[runnervmmtnos:32218] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c9ec9eb2c]
[runnervmmtnos:32218] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c9ec4527e]
[runnervmmtnos:32218] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c9ec288ff]
[runnervmmtnos:32218] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c9f0a5ff5]
[runnervmmtnos:32218] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c9f0bb0da]
[runnervmmtnos:32218] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c9f0a5a55]
[runnervmmtnos:32218] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c9f0a5a6f]
[runnervmmtnos:32218] [ 8] plumed(+0x146dd)[0x55f0fb0e26dd]
[runnervmmtnos:32218] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c9ec2a1ca]
[runnervmmtnos:32218] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c9ec2a28b]
[runnervmmtnos:32218] [11] plumed(+0x15365)[0x55f0fb0e3365]
[runnervmmtnos:32218] *** End of error message ***
</pre>
{% endraw %}
